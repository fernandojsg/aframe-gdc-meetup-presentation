<!-- .slide: data-background="media/img/aframe.jpg" -->

<div class="talk-title">
  <h1>A-Frame</h1>
  <p>A web framework for building VR experiences</p>
  <p class="talk-info">
    @dmarcos | @andgokevin | Mozilla VR | **aframe.io**
  </p>
</div>

<!-- NOTES -->
- Launched December 2015
- Why:
  - Onboard web developers into the 3D and VR world with easy-to-use tools
  - Easy for web developers to create VR content, without graphics knowledge
  - Prototype and experiment WebVR and VR UX faster
  - Vehicle to kickstart WebVR ecosystem

------

# A-Frame

<div class="captioned-image-row">
  <div>
    <img data-src="media/img/github.png">
    <i>125 contributors 4800+ Stargazers</i>
  </div>
  <div>
    <img data-src="media/img/slack.png">
    <i>3000 members on Slack</i>
  </div>
  <div>
    <img data-src="media/img/scene-collage-circle.png">
    <i>100s of featured projects</i>
  </div>
</div>

24 PRs open / 956 PRs closed.

241 issues open / 1228 issues closed.

<!-- NOTES -->
- Open source and inclusive project
- Most work done on GitHub
- Active community on Slack to share projects, interact, hang out, seek help
- Featured projects on the `awesome-aframe` repository and *A Week of A-Frame* blog

------

<!-- .slide: data-background="media/img/venn-diagram.gif" -->

<!-- NOTES -->
- A-Frame scene by Ada Rose Edwards running from inside my HTML slides
- Works on desktop, Android, iOS, Samsung Gear VR, Oculus Rift, HTC Vive
- Could open up the DOM Inspector to change values live
- Since it's just HTML...

------

# Entity-Component-System

<!-- .slide: data-background="media/img/minecraft-blocks.png" -->

<!-- NOTES -->
- Is an entity-component framework
- Popular pattern in game development, used by Unity
- All objects in scene are **entities** that inherently empty objects. Plug in
  **components** to attach appearance / behavior / functionality
- 2D web where every element was fixed
- 3D/VR is different, objects of infinite types and complexities, need an easy way to build up different kinds of objects

------

# Registry

<!-- .slide: data-background-color="#333" -->

Curated collection of A-Frame components.

<a class="stretch" href="https://aframe.io/aframe-registry">
  <video loop data-src="media/video/registrypreview.mp4" data-autoplay></video>
</a>

<!-- NOTES -->
- Collecting them into the A-Frame registry
- Like a store of components that we make sure work well
- People can browse and search for components or install them....

------

# Registry

<!-- .slide: data-background-color="#333" -->

Curated collection of A-Frame components.

<video loop data-src="media/video/leaphands.mp4" data-autoplay></video>

------

# Inspector

<!-- .slide: data-background="media/img/metaverse.png" -->

<div class="stretch" data-aframe-scene="scenes/80s.html"></div>

------

# glTF Support

```html
<a-entity gltf-model="src: model.gltf"></a-entity>
```

![](/media/img/gltf.png)

------

<!-- .slide: data-background="media/img/header.png" -->

# Community Examples

https://aframe.io/blog/

------

<!-- .slide: data-background="media/img/syria.gif" -->

# Journalism - *Fear of the Sky*

Amnesty International UK

------

<!-- .slide: data-background="media/img/mars.jpg" -->

# Journalism - *Journey to Mars*

The Washington Post

------

<!-- .slide: data-background="media/img/citybuilder.gif" -->

# Sandbox - *City Builder*

@kfarr

------

<!-- .slide: data-background="media/img/adit.gif" -->

# Data Visualization - *Adit*

@datatitian

------

<!-- .slide: data-background="media/img/a-blast.gif" -->

# Gaming - *A-Blast*

@mozillavr

------

<!-- .slide: data-background="media/img/ux.gif" -->

# Prototyping - *UI Widgets*

@whoyee

------

<!-- .slide: data-background="media/img/math.gif" -->

# Mathematics - *MathworldVR*

@sleighdogs

------

<!-- .slide: data-background-color="#222" data-background-video="media/video/ghosttrain.mp4" data-background-video-loop="true" -->

# Entertainment - *Ghost Train*

@realisetweets

------

<!-- .slide: data-background="media/img/apainter.gif" -->

# Art - *A-Painter*

@mozillavr

------

<!-- .slide: data-background="media/img/screenvr.gif" -->

# Utility - *ScreenVR*

@jonathanzwhite

------

<!-- .slide: data-background="media/img/ar.gif" -->

# AR - *aframe-ar.js*

@jerome_etienne

------

<!-- .slide: data-background="media/img/webvrstudio.png" -->

# Tools - *WebVR Studio*

@webvrstudio

------

<!-- .slide: data-background="media/img/shaders.gif" -->

# Shaders - *ShaderFrog*

@machenmusik

------

<!-- .slide: data-background-video="media/video/livetour.mp4" data-background-video-loop="true" -->

# Real Estate - *Live Tour*

iStaging

------

<!-- .slide: data-background="media/img/senseofpromise.gif" -->

# Ownership - *Sense of Promise*

@akupresanin

------

<!-- .slide: data-background="media/img/cadavr.gif" -->

# Education - *CadaVR*

@drryanjames

------

<!-- .slide: data-background="media/img/2017nyc.gif" -->

# *2017 Holiday Snow Globe*

@ronikdesign

------

<!-- .slide: data-background="media/img/tango.jpg" -->

# *Project Tango to WebVR*

@utopiah

------

# What's Coming?

- Link traversal
- WebVR shipped and enabled on Firefox 54 (2017-06-13)

![](/media/img/linktraversal.gif)

------

<!-- .slide: data-background="media/img/saturdaynight.gif" -->

# Motion Capture - *A Saturday Night*

[Ready to dance?](http://swimminglessonsformodernlife.com/a-saturday-night/?url=https://ucarecdn.com/b1435e07-36d0-491b-8c9e-0c933aaf32aa/)

@mozillavr

------
