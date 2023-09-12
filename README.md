# Logoscale

## 📄 Abstract

During the height of the Coronavirus pandemic, I found myself doing a ton of work with [ESRGAN](https://github.com/xinntao/ESRGAN), an AI-powered image superscaling tool.

ESRGAN was invented to help governments see more detail with older surveillance satellites, but eventually declassified and brought into the open source world. The principle is that a developer creates situation-specific models by showing the AI two sets of images — the original ones, and larger versions of the image. The AI then calculates the patterns of the lower-resolution images, and then corresponds them to areas and textures that it sees in the source imagery.

Tinkerers in the space discovered that someone can create utility models from banks of large, high resolution images, then saving them into highly compressed or highly interlaced states. This gave way to cool stuff like methods for removing JPEG compression from images, or even adding texture *back* to the videos.

I got really absorbed into making my own tools that could aid in some otherwise daily design tasks. **I started thinking about the daily frustrations I had, and being sent a terribly compressed, JPEG or PNG logo instead of a vector format was chief among them**. But, the issue is, oftentimes a client or a stakeholder will send you an inferior format, and then disappear off the face of the planet. **With this in mind, I set out to make a tool that could superscale the low-resolution logos we get sent to something vectorized that can be relied on in a pinch to get a job all the way to completed, without needing to wait around for someone to find a logo file that may not even exist anymore.**

The result is `LogoScale`, a FLOSS upscaling model for use with ESRGAN-compatible tools.

## Reference

This is a mirror of https://msprout.notion.site/LogoScale-A-Method-for-Vectorizing-Small-Crappy-Logos-dc0035b7473c44f8b94ffc4026d286c0 written by https://donaberger.xyz/