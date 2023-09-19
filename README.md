
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/NZ Photography Logo.png" alt="Logo" width="300
    " height="120">

  <h3 align="center">Photography Website </h3>

  <p align="center">

<br>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<img src="images/Screenshot 9_19_2023 3_43_41 PM.png" alt="Home Page" >

This is a photography website for an amateur to beginner professional photographer. There is a main page which includes a hero and about me section. Further down the page is a slide show that incorporates recent works. Finally an instagram scraper pulls the six most recent posts to the home page to keep content current. Headers and footers are also seen with navigation and social media links. 
<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

Here are screen shots of each of the features and pages. First will be the elements on the home page followd by the gallery with a masonry display of photographs, followed by a pricing page, and finally a contact me page. 

<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_44_15 PM.png" alt="Home Page" >
Here is the home page with a carousel gallery that is automatic and clickable. Time is adjustable as well. There is space for further discussion of the goals of the photographer. I debated actually filling this out but in the end settled on Loren Ipsum so other could customize the layout and text to their liking as needed. I also went back and forth on the hero vs a landing page but ultimatley settled on a hero due to potential of scaring off new site goers. The carosel was also interesting to parse out and I ended up using bootstrap rather than an open source option. The bootstrap 5 version is great and has plenty of customization available. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_44_23 PM.png" alt="Home Page" >
Here is the behold.so instagram scraper embedded widget. This is a free open source project that allows for up to 1.2k views before adding pricing. There are multiple layouts for the displayed posts. Instagram and META in general make it difficult to access APIs and embed them. I made a time and money decision to go with an open source option. It works and will scale with cost as needed. There are other options and they can always be created from scratch. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_44_40 PM.png" alt="Gallery" >
Here is the gallery example. The pictures would be customized to the subjects with their names and occasion. There is a grayscaled effect with text that appears on mouse over. This entire appearing object is clickable to link to the main gallery. I spent the most time on the gallery, lightbox, and masonry layout section. It was difficult to accomplish and many other website builders do it better. It was a great learning exerpience with different photo sizes and layouts and making it all work. Bootstrap and flexbox were enourmously helpful during this frustrating time. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_44_49 PM.png" alt="Gallery" >
Here is the gallery with photos displayed in a masonry layout. Each photo is clickable and opens up to a lightbox feature from bootstrap. See above for information on the masonry layout. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_44_51 PM.png" alt="Gallery" >
Here is the lightbox effect. Once the layout was completed the lightbox effect was comparitively easy to add. Again there are open source options but Boostrap comes through again. Some open source options have more features and look a bit better but they have costs in many cases. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_45_10 PM.png" alt="Pricing" >
The pricing page can be customized to many different layouts to accoomodate different styles of photography. This was generic and can can be customized further or less with flexbox or any grid layout. Cards were helpful for this creation. 
<img src="images/Nicole Zauski Photography - Google Chrome 9_19_2023 3_45_21 PM.png" alt="Contact" >
Finally here is the contact me page complete with email active form submission with serverless backend powered by Formspree.io. While backend with Flask would have been more computer science I chose to use a serverless backend with open source software since static sites are cheaper to deploy and often times free minus their domain name. I felt that this allowed for more users and they can customize their email needs. Obviously a Flask backend would be easy to setup and add to this project and the user would just need to find server hosting. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

dzauski585 

Project Link: [https://github.com/dzauski585/Photo](https://github.com/dzauski585/Photo)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* My wife for her support and wonderful pictures
* CS50 course and Instructors/Staff
* Dr. David Malan
* Harvard University
* Behold.so (Open source instagram scraper/embed)
* Formspree.io (Open source serverless form handling)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com

