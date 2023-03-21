# Lectures of Physics 113 - Computational Physics

This repository contains the source files and Jupyter notebooks used in the course Physics 113: Computational Physics
taught by Tom Abel.

Spring quarter 2022/20023 academic year, April-June 2023

To build the book after you added more content (or cloned the repository the first time) use

```bash
Physics-113-Book> jupyter-book build ./
```
and it will be found in your local ```_build/html``` directory. 

To publish it to the website we execute in the main directory of the repository. 

```bash
ghp-import -n -p -f _build/html
```