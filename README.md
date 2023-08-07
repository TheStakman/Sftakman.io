lynnsanity.io
=============

### Set up SvelteKit

```sh
npm init svelte@next svelte-kit
cd svelte-kit
npm install @sveltejs/adapter-node@next --save-dev
# change auto to node
nvim svelte.config.js
```

### Build and run image locally

```sh
podman build -f Dockerfile -t lynnsanity:1.0.0
podman run -it --rm --name sveltekit-docker -p 3000:3000 lynnsanity:1.0.0
```

### Push image to your registry

`podman push lynnsanity/lynnsanity.io:<tag>`

