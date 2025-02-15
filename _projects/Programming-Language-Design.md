---
title: "A quick comparison among Python, Cython, and the C languages"
collection: projects
---
***A quick comparison among Python, Cython, and the C languages. A Programming Assignment regarding the Programming Language Design course***

# Runtime analysis of code with plotting
A quick comparison among Python, Cython, and the C languages.
A Programming Assignment regarding the Programming Language Design course.
(Fall 2021)

* [Github repo](https://github.com/CenaAshoori/sort_cython)
  

<!-- TABLE OF CONTENTS
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#how-it-works">How it Works</a></li>
    <li><a href="#testing-and-screenshots">Testing and Screenshots</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details> -->



<!-- ABOUT THE PROJECT -->

## About The Project
In this project, we are comparing the execution time of four different approaches, including :
- Pure C
- Optimized Cython
- Non-Optimized Cython
- Pure Python

### Built With


* [Python](https://www.python.org)
* [VS Code](https://code.visualstudio.com)
* [Cython docs](https://cython.org/#documentation)
* [Matplotlib](https://matplotlib.org/stable/gallery/index.html)
* thanks to [Color hunt](https://colorhunt.co)



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Python 3, An IDE 
* C compiler (gcc, ...)
* Cython lib
* matplotlib 

### Installation

- Clone the repo
 ```sh
   git clone https://github.com/CenaAshoori/sort_cython
 ``` 

- Install requirement :
```bash
pip install cython
pip install matplotlib
```

<!-- USAGE EXAMPLES -->
## Usage
Cython enables you to create extension modules from **Python**, **Cython**, or **C** code to a compiled version of it, which is much faster compared to just using python. 

Numpy, for example, uses this method  


  
## How it Works
we have implemented bubble sort in 4 diffrent methods : 
1. C
2. An optimized Cython
3. Non optimized Cython
4. Python
  
 
Initially, you will need to build these three codes, and after that, you can import them into the `run.py` file.  

```bash
  python setup.py build_ext --inplace
```
  
Check out the `Cython` documentation to learn how it works, and how you can change the bubble sort to a different algorithm!  
Good luck!
  
## Testing and Screenshots  
  
  
  ### Screenshots:  
  
  <img src="https://raw.githubusercontent.com/CenaAshoori/sort_cython/main/doc/plot/Figure_2.png" width="875" height="500">
  <img src="https://raw.githubusercontent.com/CenaAshoori/sort_cython/main/doc/plot/big_input.png" width="875" height="500">
  <img src="https://raw.githubusercontent.com/CenaAshoori/sort_cython/main/doc/plot/small_input.png" width="875" height="500">
  
  
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


  

## Author Info:  

| First and Last Name            | Github                                  |
| ------------------------------ | --------------------------------------- |
| Mohammad Hossein(Cena) Ashoori | [Link](https://github.com/CenaAshoori)  |
| Mohammad Mehdi Afkhami         | [Link](https://github.com/mohmehdi)     |
| Parsa KamaliPour               | [Link](https://github.com/benymaxparsa) |






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- [contributors-shield]: https://img.shields.io/github/contributors/CenaAshoori/sort_cython?style=for-the-badge
[contributors-url]: https://github.com/CenaAshoori/sort_cython/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CenaAshoori/sort_cython?style=for-the-badge
[forks-url]: https://github.com/CenaAshoori/sort_cython/network/members
[stars-shield]: https://img.shields.io/github/stars/CenaAshoori/sort_cython?style=for-the-badge
[stars-url]: https://github.com/CenaAshoori/sort_cython/stargazers
[issues-shield]: https://img.shields.io/github/issues/CenaAshoori/sort_cython?style=for-the-badge
[issues-url]: https://github.com/CenaAshoori/sort_cython/issues
[issues-closed-shield]: https://img.shields.io/github/issues-closed/CenaAshoori/sort_cython?style=for-the-badge
[issues-closed-url]: https://github.com/CenaAshoori/sort_cython/issues?q=is%3Aissue+is%3Aclosed
[pull-req-shield]: https://img.shields.io/github/issues-pr/CenaAshoori/sort_cython?style=for-the-badge
[pull-req-url]: https://github.com/CenaAshoori/sort_cython/pulls
[pull-closed-shield]: https://img.shields.io/github/issues-pr-closed/CenaAshoori/sort_cython?style=for-the-badge
[pull-closed-url]: https://github.com/CenaAshoori/sort_cython/pulls?q=is%3Apr+is%3Aclosed
[milestones-shield]: https://img.shields.io/github/milestones/all/CenaAshoori/sort_cython?style=for-the-badge
[milestones-url]: https://github.com/CenaAshoori/sort_cython/milestones
[license-shield]: https://img.shields.io/github/license/CenaAshoori/sort_cython?style=for-the-badge
[license-url]: https://github.com/CenaAshoori/sort_cython/blob/main/LICENSE
 -->
