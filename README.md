# Feed Me Branding

Just a simple repository for maintaining some of our branding assets -- logos, icons, etc.

## What to save here

Ideally try to save the original source vector graphic files here. We'll keep those in the "src" (source) folder like on typical software development projects. Normally you wouldn't commit any programattically generated files, but in this case I think it's ok since not everybody is a developer and not everybody will be able to run all of the "build" processes that might get added in here. 

## Javascript and pwa-asset-generator

I ran across a blog about this tool when I was looking into managing our various icons and splash screens. There are some online tools that take an image and generate a zip file with many of the icon formats and resolutions you'll want, but I'd rather be able to run the process remotely and not have to rely on an online tool. [pwa-asset-generator](https://github.com/onderceylan/pwa-asset-generator) does just that by opening the images/html you tell it to with the styles you want in a headless browser window using the window dimensions of the target image you want to produce and then just takes a screenshot. 

I imagine there are other tools that use different approaches and some of them may be better for what we want, but atleast this gives us somewhere to start.