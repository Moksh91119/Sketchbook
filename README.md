# 📒 Sketchbook

Simple web based game engine built on [three.js](https://github.com/mrdoob/three.js) and [cannon.js](https://github.com/schteppe/cannon.js) focused on third-person character controls and related gameplay mechanics.

Mostly a playground for exploring how conventional third person gameplay mechanics found in modern games work and recreating them in a general way.

## Features

* World
	* Three.js scene
	* Cannon.js physics
	* Variable timescale
	* Frame skipping
	* FXAA anti-aliasing
* Characters
	* Third-person camera
	* Raycast character controller with capsule collisions
	* General state system
	* Character AI
* Vehicles
	* Cars
	* Airplanes
	* Helicopters


## Usage

You can define your own scenes in Blender, and then read them with Sketchbook. Sketchbook needs to run on a local server such as [http-server](https://www.npmjs.com/package/http-server) or [webpack-dev-server](https://github.com/webpack/webpack-dev-server) to be able to load external assets.

<!-- #### Script tag -->

1. Import:

```html
<script src="sketchbook.min.js"></script>
```

2. Load a glb scene defined in Blender:

```javascript
const world = new Sketchbook.World('scene.glb');
```


## Getting Started

1. Get the LTS version of [Node.js](https://nodejs.org/en/) 16
2. Clone the Repository `git clone https://github.com/Moksh91119/Sketchbook.git`
3. Run `npm install`
4. Run `npm run dev`
5. Make changes and test them out at http://localhost:8080


## Contact

If you have any questions or need further assistance, feel free to contact me:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Learn more about me and explore my other projects.

---

Feel free to open issues or contribute to the project. Your feedback and contributions are always welcome!
