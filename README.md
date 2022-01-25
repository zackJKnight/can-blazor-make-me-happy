# can-blazor-make-me-happy

A 'lunch and learn' talk for my friends at work.

## Talking Points

We want to give our customers tools that save them time and give them superpowers.

Part of doing this is to choose a tech stack that we can be effective with.

But effectiveness in WHATEVER stack it is... boils down to our ability to THINK. Problem solving happens in our thoughts. The tools can bring action from our thoughts.

We could say another part of delivering great tools to our customers is making an effort to keep balance in our thoughts to continue at a consistent pace. For as long as we shall toil. Maybe some of you do this effortlessly. This talk has something for you too; thanks for sitting through this part for the rest of us.

If I am unhappy, I have additional thoughts that invade my focus.

When I am happy, and I am having fun I can THINK FASTER.

So how do we spend more time being happy at work?

<blockquote class="twitter-tweet" data-partner="tweetdeck"><p lang="en" dir="ltr">The ultimate source of happiness is within us. Not money, not power, not status. Some of my friends are billionaires, but they are very unhappy people. Power and money fail to bring inner peace. Outward attainment will not bring real inner joyfulness. We must look inside.</p>&mdash; Dalai Lama (@DalaiLama) <a href="https://twitter.com/DalaiLama/status/1479385216561004548?ref_src=twsrc%5Etfw">January 7, 2022</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Our team has learned about React. Can anyone remember something that you liked from the React training- or something you did on your own WITH the training?

I suspect that we did not get enough hands-on time to evaluate whether we enjoy using it.

### History

Allow me to paint a fuzzy picture for the sake of brevity.

We don't need to go all the way back through the history of the web. But for the past 25 years or so, .NET developers have been making software that for better or worse is used via the browser. You may have heard of some of the technologies that made this happen - Classic ASP, Web Forms (.aspx files with a code behind), MVC, Silverlight, ASP.NET Core MVC.

With the exception of Silverlight, you were using .NET to render HTML on the server. Updates could be requested using AJAX. Every visual update or rerender or DOM change was a round trip to the server.

To get anything to change quickly in the UI, you could (and still can) use Javascript.

Silverlight could run your code in the browser and update the view without hitting the server. But it required a plugin. Which was disallowed by browsers for security concerns (if you were invested in Silverlight development, you may have more to say about this).

Since Silverlight became unsupported, .NET developers took a detour to learn javascript frameworks like Angular etc.

Blazor is the stack that brings client side rendering with .NET code.

It can render strictly on the server too, if that's all you need. But the visual layout is made with HTML and CSS. P.S. it can also be prerendered on the server before being sent to the browser to improve responsiveness.

### Anatomy

Files, markup, code, components, styling, etc.

### State Management

How does Blazor manage state?

### Tools

IDEs, Build tools, SDKs, Packages

### Community

Learning more, shared controls, help.

## Source Material

### Demo Videos

[Steve Sanderson, Blazor Papa Blows Your Mind](https://youtu.be/kesUNeBZ1Os)

[SkiaSharp in Blazor WASM](https://www.youtube.com/watch?v=lVWQkpcVEWQ&list=PLdo4fOcmZ0oX-DBuRG4u58ZTAJgBAeQ-t&index=2)

[Dan Roth, program manager at MS gives an overview of blazor in .NET 6](https://youtu.be/GKu-vRxOWr8)

[Jason Taylor, covers Blazor in .NET 6](https://youtu.be/lRYrhj9lwQk)

[Tim Corey, Blazor Updates in .NET 6](https://youtu.be/wT9EOfLghlY)

## Articles Read

[Razor Syntax](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/razor?view=aspnetcore-6.0)

[Emscripten - the Blazor WebAssembly Toolchain](https://emscripten.org)
[Linking Native Code into Blazor WASM](https://visualstudiomagazine.com/articles/2021/10/15/aspnet-update.aspx)

[Prerendering Blazor to target Static Website in the Publish Step](https://dev.to/j_sakamoto/pre-render-blazor-webassembly-on-static-web-hosting-at-publishing-time-50d8)

## Happiness Research

### Happiness in other Cultures

[Happiness - Japanese Ikigai](https://youtu.be/Zxj3P0enJNQ?t=337)

[Yoga](https://youtu.be/akvENoujVEY)

[Celebrities on Money and Fame](https://youtu.be/KqtRTc3VYq4)

### Happiness in Buddhism

"Stop attributing our happiness to what's going on externally" - Gen Kelsang Nyema

"Happiness and unhappiness are states of mind and therefore their root causes cannot be found outside the mind." - Gen Kelsang Nyema's teacher

### Happiness in Islam

Update - I have since learned that Nouman Ali Khan has been #metoo'd.

"Allah summarizes the things we run after that we think will make us happy: A child thinks they'll be happy when they play. A little older when they get entertained. A little older when they feel beautiful. A little older when they can show off they've accomplished something. A little older when they feel like they have financial stability." - Nouman Ali Khan

"At the end is either intense punishment- You won't get used to this- Or forgiveness from Allah; incredible contentment. You will be at peace. You will not look for the next thing." - Nouman Ali Khan

"You're not going to be at peace here. we'll always be looking for the next thing until dirt fills our stomachs." - Nouman Ali Khan

### Blazor Projects in the Wild

[This app shows blazor hosting cesium maps via javascript. Not much Blazor. Mostly JS.](https://github.com/HyunSeongKil/CesiumBlazorWasm/blob/master/wwwroot/index.html)



Time spent on talk:
1/8/22 - 1 hour
1/9/22 - 2 hours
1/15/22 - .5 hour
1/16/22 - .5 hour
1/18/22 - 1 hour