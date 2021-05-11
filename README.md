# slug-maker

<!-- TABLE OF CONTENTS -->
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
NPM package that cleans and sluggifies any string, see the **live** package [here](https://www.npmjs.com/package/slug-maker) 


### Built With
* [JavaScript](https://www.javascript.com/)
* [NPM](https://www.npmjs.com/)


<!-- GETTING STARTED -->
## Getting Started

To get the package installed in your project, follow these simple steps.

### Prerequisites

- NPM 


### Installation

1. Install this NPM package in your exisitng node application 
   ```sh
   npm install slug-maker
   ```
   

<!-- USAGE EXAMPLES -->
## Usage

#### Case to Slug 

A slug is a human-readable, unique identifier, used to identify a resource instead of a less human-readable identifier like an id . 

You use a slug when you want to refer to an item while preserving the ability to see, at a glance, what the item is, and should be a unique part of a URL.

**Project File** 
```JavaScript
const {makeSlug} = require('slug-maker');

console.log(makeSlug("TestING,   HoW I$s Th1s L00KiNg?!?!?!?!@#$#@*&"));
```

**Terminal**
```dash 
$ node index.js 
```

**Returns**
```dash 
$ testing-how-is-th1s-l00king
```

Notice that all non-alphanumerical characters have been removed and extra spaces have been handled. 

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/ellojess/slug-maker/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request using this [template](https://github.com/embeddedartistry/templates/blob/master/oss_docs/PULL_REQUEST_TEMPLATE.md)



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Jessica Trinh - [@ellojesss](https://twitter.com/ellojesss) - jtjessicatrinh@gmail.com

Project Link: [https://www.npmjs.com/settings/ellojess/packages](https://www.npmjs.com/settings/ellojess/packages)
