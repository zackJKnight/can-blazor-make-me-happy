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

Well, they also had Xamarin Forms, which allowed .NET developers to write XAML UIs and deploy to mobile platforms. But you'd need something like [Ooui](https://github.com/praeclarum/Ooui) to [bring it to the web](https://s3.amazonaws.com/praeclarum.org/wasm/index.html).

Blazor is the stack that brings client side rendering with .NET code to the browser. And we can get it back to the desktop or mobile either with Xamarin or Electron (many people poo poo this approach, but it's A solution).

It can render strictly on the server too, if that's all you need. But the visual layout is made with HTML and CSS. P.S. it can also be prerendered on the server before being sent to the browser to improve responsiveness.

Why is this remotely interesting to me, a powerful wizard of .NET Desktop development; mage of the Microsoft stack?

Would you like to stop opening Install Shield? Have you ever tried to use WiX to build an installer? Wouldn't it be cool to put a bugfix into the user's hands moments after you test it, rather than months?

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

"You're not going to be at peace here. we'll always be looking for the next thing until dirt fills our stomachs." - Nouman Ali Khan

### Blazor Projects in the Wild

[This app shows blazor hosting cesium maps via javascript. Not much Blazor. Mostly JS.](https://github.com/HyunSeongKil/CesiumBlazorWasm/blob/master/wwwroot/index.html)

[Trains Game](https://wengier.com/Trains.NET/)



Time spent on talk:
1/8/22 - 1 hour
1/9/22 - 2 hours
1/15/22 - .5 hour
1/16/22 - .5 hour
1/18/22 - 1 hour
1/30/22 - 3 hours
1/31/22 - 1 hour (skia - fill points in a circle)

## Graphics

[ANGLE](https://chromium.googlesource.com/angle/angle/+/main/README.md)

## Points that Make Me Happy

## Points that Make Me Unhappy

IDE syntax checking and compile error intellisense. Maybe this is a problem with Skia, but in VS for Mac, there was no build error. In visual studio there was a build error, but nothing in the editor gave an indication of the problem.

## Inspiration

[Polygon Explorer](https://www.visnos.com/demos/polygon-explorer)

[Distribute Points in a Circle](https://www.wolframcloud.com/objects/demonstrations/SunflowerSeedArrangements-source.nb)

```csharp
const double GoldenRatio = 1.61803398874989484820458683436;
```
