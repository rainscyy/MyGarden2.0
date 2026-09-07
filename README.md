# MyGardens 2.0 🌱

A single-file pixel-art productivity prototype where tasks and focus sessions become plants in an isometric garden.

**[Open demo](https://rainscyy.github.io/MyGarden2.0/)** · HTML / CSS / JavaScript

## Explore

Move from the forest overview into a category garden, add a task, and start a focus session. Completed and failed tasks produce different plant states. The prototype includes a floating timer, task details, and category-specific garden views.

Task and garden state is saved in browser `localStorage`. There are no accounts or cross-device synchronization; clearing browser storage removes the local records.

## Run locally

With Python 3 installed, from this repository:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://localhost:8000`. The entry point is **`index.html`**, which contains the interface, styles, and interaction logic. No package installation or build step is required.

## Design iteration

This version explores a lightweight, isometric interface. [MyGarden](https://github.com/rainscyy/MyGarden) explores activity records; [3.0](https://github.com/rainscyy/MyGardens3.0) develops a React focus-and-growth loop. [Our Gardens](https://github.com/rainscyy/MyGarden4.0) extends the metaphor into shared agent activity.

These are prototype experiments, not evidence that gamification improves productivity.

By Chunyu (Raine) Sha · [Portfolio](https://rainesha.my.canva.site/)
