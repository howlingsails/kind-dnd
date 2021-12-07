# kind-dnd - WORK IN PROGRESS
Using Local Kind to run a bunch of useful dnd tools to build worlds

## Agenda

[x]  Windows Kind Kubernetes Cluster Running on Local Machine
[x]  Get Town Generator Running in Docker.
[~]  Get Map Geneator Running in Docker.
[ ]  Build Kubernetes Yaml Config for deployment to king
[ ]  Link Map to Town Generator with more seeds
[ ]  Link Town Generator to generate stored charactors for campains
[ ]  Add Plot Generators

## Setup

### Step 1 - Setup your development environment
Assuming you have kind setup
Development IDE 
Git ssh authorization setup... 

### Step 2 - Clone the Github repo

```
git clone git@github.com:howlingsails/kind-dnd.git
```

### Step 3 - Add Submodules
Add Submodules 
If you want to fork these ```repositories``` then update the names here

```
cd kind-dnd
git submodule add git@github.com:howlingsails/Fantasy-Map-Generator.git
git submodule add git@github.com:howlingsails/dnd5e-town-generator.git
git submodule add git@github.com:howlingsails/opendnd.git
```


