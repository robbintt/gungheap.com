# gungheap.com

This is a blog.

"Gung Heap" is a quasi-[portmanteau](https://en.wikipedia.org/wiki/Portmanteau) of "Gung Ho" and "Dung Heap". It is inspired by the [Programmer Archaeologists](https://en.wikipedia.org/wiki/A_Deepness_in_the_Sky#Interstellar_culture) of the Qeng Ho, pronounced `Chung Ho` (ref: "A Fire Upon the Deep", Vernor Vinge) and rhyming with "Gung Ho".

The name is originally from our [Noisebridge Gung Heap](https://github.com/noisebridge/gung-heap).  I'm reusing it for my blog because I still like the name.


## Github Pages

The [github pages](https://robbintt.github.io/outlines/) are rendered with [portray](https://timothycrosley.github.io/portray/) and [mkdocs-awesome-pages-plugin](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin)

- Portray is configured in `pyproject.toml`
- requiring the project to have a `docs` directory for now (maybe there is some hack to get rid of the `docs/` top level directory.

### Rebuilding Locally (debugging only)

- make a virtualenv
  - publish with the command: `portray on_github_pages`
- Rebuild the portray virtualenv by simply installing `portray` and `mkdocs-awesome-pages-plugin`.

### Resources

- [github pages quickstart](https://docs.github.com/en/pages/quickstart)
