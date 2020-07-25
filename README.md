# Sprint Toolkit

[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<img src="https://alvesmog.netlify.app/images/uploads/sprinttookit.gif" alt="application image" title="Application GIF">
[Link to the application](https://alvesmog.github.io/sprinttoolkit/)

Developed using vanilla JS, this tool uses combinatory analysis with repetition in order to facilitate User Stories ranking.


# Usage

The calculation is done using the following mathematical formula to evaluate how many combinations are possible considering the input constraints:

<div style="text-align:center"><img src="https://alvesmog.netlify.app/images/uploads/sprinttoolkit-equation.png" /></div>

There are two methods of combining, you can choose either the Fibonacci series or a Complexity vs Uncertainty as follows:

<div style="text-align:center">
  <img src="https://alvesmog.netlify.app/images/uploads/fibonacci-series.png" height="200" width="auto"/>
  <img src="https://alvesmog.netlify.app/images/uploads/complexity-uncertainty.png" height="200" width="auto"/>
</div>

Depending on which one you choose, the formula will be fed by an array containing the corresponding mathematical set.

Meanwhile, the number os user stories will be the number of elements in each combination.

The last constrain is the total sum of all elements - e.g., a sprint that contains 8 user stories and in which the total sum of the US's points should be 70 will have the following number of possible combinations, depending on which method you choose:

Fibonacci: 74
Complexity vs Uncertainty: 62
After the calculation, all possible combinations are shown at right side of the screen.

## Contributing

Want to contribute? Great! Any contributions you make are greatly appreciated. To do so, follow these steps:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourGreatFeature`)
3. Commit your Changes (`git commit -m 'Add some GreatFeature'`)
4. Push to the Branch (`git push origin feature/YourGreatFeature`)
5. Open a Pull Request

License
----
Distributed under the MIT License. See `LICENSE` for more information.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/alvesmog/sprinttoolkit.svg?style=flat-square
[contributors-url]: https://github.com/alvesmog/sprinttoolkit/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/alvesmog/sprinttoolkit.svg?style=flat-square
[issues-url]: https://github.com/alvesmog/sprinttoolkit/issues
[license-shield]: https://img.shields.io/github/license/alvesmog/sprinttoolkit.svg?style=flat-square
[license-url]: https://github.com/alvesmog/sprinttoolkit/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/guilherme-augusto-alves-1057b5b1/
