# Grid Framework
A basic grid framework representing a 12 column grid. It has been used to clone the microverse dashboard "view progress" section found [here](https://wathigo.github.io/micoverse-dashboard/)

## Preliquisites
1. SASS
2. CSS3
3. Browser
4. Code Editor

## Getting Started
1. Clone the repository with the command
  ```bash
      $ git clone https://github.com/sonegillis/grid-framework.git
  ```
2. Navigate to the sass directory
  ```bash
      $ cd sass
  ```
3. The folder consist of the __helpers__ directory containing the *_mixins.scss* for mixins, *_placeholders.scss_* containing the placeholders and the *_variables.scss* all imported in the *main.scss*.
4. The folder also contains the __layouts__ directory where the *_grids.scss* is found.

## Usage
1. Create a div or section with __class="row gutter-size"__ for a row containing columns with the smallest gutter size
  * __class="row gutter-size"__ has fixed guttter size of 10px;
  * __class="row gutter-size-md"__ has fixed guttter size of 20px;
  * __class="row gutter-size-lg"__ has fixed guttter size of 30px;
2. Inside the div or section you can create div or sections with __class="col-x"__ with x ranging from __1__ throught __12__

## Contributors
1. [Sone Gillis](https://www.github.com/sonegillis)
2. [Simon Wathigo](https://www.github.com/wathigo)
