# :student: PhD Thesis Template :open_book:

Hello! :wave: Welcome to my LaTeX thesis template repository. 

## :thinking: Why does this exist?

So, it’s time to begin writing up you PhD but there’s a problem: your university doesn’t have a LaTeX thesis template. You don’t want to go near MS Word but you don’t want to spend precious writing time creating a template of your own.

Well, you're in luck! 💡

I had _exactly_ the same issue during my PhD; so I created a minimal template that can be adapted by others for their own needs.

## :building_construction: Structure

While smaller LaTeX documents can all be contained in a single .tex file, this isn't _that_ practical when it comes to a longer form piece like a thesis. So, the template has a compartmentalised structure:

- Front: this includes all the preamble to the thesis body itself (e.g. abstract, title page etc.)
- Back: as an example, this includes tables but could contain appendicies or any matter to come after the main body
- Main: in here, there's a separate .tex files for each major section. I've included chapters as an example but could be easily modified
- packages.tex: where you can list all required pacakges needed to compile your thesis
- thesis.tex: the junction file that brings together all other components of the thesis

If you'd like to delve deeper into the files themselves, simply click on file in the directory tree below to be taken to that file's specific source code 👇

### :evergreen_tree: File tree overview :open_file_folder:

- __phd\-thesis\-template__ (./Screenshots and README.md are removed to leave only files relevent to you)
   - __Back__
     - [tables.tex](Back/tables.tex)
   - __Front__
     - [abstract.tex](Front/abstract.tex)
     - [acknowledgements.tex](Front/acknowledgements.tex)
     - [declaration.tex](Front/declaration.tex)
     - [dedication.tex](Front/dedication.tex)
     - [title.tex](Front/title.tex)
   - __Main__
     - [chapterone.tex](Main/chapterone.tex)
     - [introduction.tex](Main/introduction.tex)
   - [packages.tex](packages.tex)
   - [thesis.pdf](thesis.pdf) :point_left: Have a look at the compiled PDF for a look at the barebones structure
   - [thesis.tex](thesis.tex)

## :memo: Licencing 

This thesis template uses the [LPPL-1.3c License](https://www.latex-project.org/lppl/lppl-1-3c/).

## :thought_balloon: Ideas? Comments?

If you have any ideas or contributions you'd like to sure, please feel free to fork this repo and submit pull requests. 👍
