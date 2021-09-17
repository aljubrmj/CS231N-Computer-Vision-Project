<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Stanford CS231N Course Final Project (Code is Confidential as it Relates to the AICC Bootcamp)</h3>

  <p align="center">
State-of-the-art wind turbine are based on voluntary surveys and self-reports. This approach is expensive, time-consuming, and prone to human error. Hence, automated high-fidelity wind turbine localization using computer vision and satellite imagery is proposed as a sustainable solution. A pipeline model is developed and evaluated to accomplish this task using two main modules: detection and localization. Detection is casted as a binary classification task, and it is performed by training a DenseNet121 network, achieving accuracy, AUROC, precision, and recall of 0.995, 0.998, 0.981, and 1.000, respectively, on the test set. Grad-CAM is used to generate heatmaps to further understand the model behavior and facilitate counting and localizing wind turbines. Semi- and weakly- supervised models are developed to use the Grad-CAM heatmaps and output count and location of wind turbines. The weakly-supervised model is found to be superior in performance with 0.907 in counting recall. It is observed that counting false negative instances are due to the fact that wind turbines sometimes appear incomplete as they occur at the edge of the tile, and that Grad-CAM heatmap signal is not sufficiently indicative in some cases. 
    <br />
    <a href="https://github.com/aljubrmj/CS231N-Computer-Vision-Project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/aljubrmj/CS231N-Computer-Vision-Project/issues">Report Bug</a>
    ·
    <a href="https://github.com/aljubrmj/CS231N-Computer-Vision-Project/issues">Request Feature</a>
  </p>
</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Name: [@MJAljubran](https://twitter.com/twitter_handle) - m.j.aljubran@gmail.com

Project Link: [https://github.com/aljubrmj/CS231N-Computer-Vision-Project](https://github.com/aljubrmj/CS231N-Computer-Vision-Project)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [] Satanford AI for Climate Change Bootcamp (This project is part of group effort within this program)
* []()
* []()



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/aljubrmj/CS231N-Computer-Vision-Project.svg?style=for-the-badge
[contributors-url]: https://github.com/aljubrmj/CS231N-Computer-Vision-Project/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/aljubrmj/CS231N-Computer-Vision-Project.svg?style=for-the-badge
[forks-url]: https://github.com/aljubrmj/CS231N-Computer-Vision-Project/network/members
[stars-shield]: https://img.shields.io/github/stars/aljubrmj/CS231N-Computer-Vision-Project.svg?style=for-the-badge
[stars-url]: https://github.com/aljubrmj/CS231N-Computer-Vision-Project/stargazers
[issues-shield]: https://img.shields.io/github/issues/aljubrmj/CS231N-Computer-Vision-Project.svg?style=for-the-badge
[issues-url]: https://github.com/aljubrmj/CS231N-Computer-Vision-Project/issues
[license-shield]: https://img.shields.io/github/license/aljubrmj/CS231N-Computer-Vision-Project.svg?style=for-the-badge
[license-url]: https://github.com/aljubrmj/CS231N-Computer-Vision-Project/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/mohammad-jabs/
[product-screenshot]: images/screenshot.png

