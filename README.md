# Better-Code-tips

\## Better Code Monday \`30/09/19\`

Good Monday to you! ☀️ Here are this week's three coding tips:

\### Tip #1 - Never forget img alt text ever again

Accessible images? Here is a neat little trick to help you not to forget adding alt text to your images!

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/49e532cf-44b0-49aa-982c-bf26b7670e00.png)

Add this CSS snippet to your global styles and you will have all the images without alternative text highlighted. Note: This will show up in production as well, so your users will see the borders if you have images without alt text. A little bit more motivation to not forget 😅

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/36060fb6-c578-4de9-bdb3-611a73ef29b6.png)

Here is an example of an inaccessible image with no alt text. 🤭

\### Tip #2 - npm install -g XXX ❌

Need to use an npm cli-tool? Probably, you would install it globally and then start using it. For example when using \*\*create-nuxt-app...\*\*

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/18a67e95-88dd-4958-b0b6-5ba0e3d2828f.png)

The problem? Global stuff is bad for your computer and your life. These global packages pile up and pollute your global scope. Instead, you can do something like this...

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/3adecd40-8070-4de3-a8db-5ef356066472.png)

Now your global env is not polluted by any temporary cli-tools. \*\*npx\*\* allows you to execute a CLI command from a module on the npm registry. Modern npm versions have \*\*npx\*\* installed automatically. Try it out and you won't regret it! 👍 You can read more about \*\*npx\*\* from their docs at \[Github\](https://github.com/npm/npx).

\### Tip #3 TS without ts 🤔 

Wants the benefits of \*\*Typescript\*\* but don't want to write typescript? Would you like to have the type-safety without refactoring your existing codebase too much? Thanks to things such as VS Code & JSDocs you can actually do that easily.

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/5a1a7155-339c-46f3-8913-5e5bde68bd7f.png)

Step 1: Enable checkJS flag in VS Code configs.

!\[\](https://gallery.mailchimp.com/5e499c75818d4611a008adfb5/images/8c116a09-9132-4fbb-9ff3-807397a89b30.png)

Step 2: Start adding JSDocs to your functions and voila you now have type checking.🎉

\### Support us Enjoyed this week's tips? Share it on twitter \[!\[share on Twitter\](http://cdn-images.mailchimp.com/social\_connect\_tweet.png)\](http://twitter.com/share?url=https%3A%2F%2Fmailchi.mp%2F5806e3994d69%2Fbetter-code-monday-300919&text=Better+Code+Monday%C2%A0%E2%9A%A1%C2%A0-%C2%A030%2F09%2F19&count=none)

That is it folks, have a good week & until next time! 👋 Ahmed P.S: Feedback or questions? Feel free to respond to this email, I read and reply to every email personally. If you have been forwarded this email, you are welcome to \[subscribe here\](http://nordschool.com/subscribe) and you will next week's tips. 👌
