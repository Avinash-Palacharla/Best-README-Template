<br />
<div align="center">
  <h1 align="center">Implementing SCD1 In Hive</h1>
</div>
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
    <li><a href="#loading-data-to-mysql">Loading Data To MySQL</a></li>
    <li><a href="#loading-data-to-hdfs">Loading Data To HDFS</a></li>
    <li><a href="#creating-hive-managed-table-and-loading-data-from-hdfs">Creating Hive Managed Table and Loading Data From HDFS</a></li>
    <li><a href="#creating-external-table-on-basis-of-dynamic-partition-and-load-data-by-performing-scd1">Creating External Table On Basis of Dynamic Partition and load data by performing SCD1</a></li>
    <li><a href="#creating-staging-table-and-performing-data-recialiation">Creating Staging Table And Performing Data Recialiation</a></li>
    <li><a href="#loading-data-again-to-the-mysql">Loading Data Again To The MySQL</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Hive1](https://user-images.githubusercontent.com/107996709/182199935-86e1f322-1a27-413c-9592-1cdea893389e.png)

A company XYZ receives the data in some file formats in local file system, the company wishes to load the data to the MySQL by creating a table and load the table data into hdfs and transfer the data from hdfs to the hive manages table and from the hive managed table the data is transferred to the hive external table by doing dynamic partition on basis of month and year and later when the new file is uploaded it will perform scd1 to make sure the updated data is only stored and then the data is transferred from external table to a staging table by performing data reconcialiation and finally load the data again to MySQL.



### Built With

Technologies and tools that are used in the project

* MySQL
* Unix Shell Scripting
* Hadoop
* Sqoop
* Hive

## Loading Data To MySQL

* For Loadng the data to the MySQL from local file system, We faced a challenge that the data is not loading with the normal login of mysql in shell scripting.
* To overcome that we have to activate two properties.





## Loading Data To HDFS

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).



## Creating Hive Managed Table and Loading Data From HDFS

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Creating External Table On Basis of Dynamic Partition and load data by performing SCD1

Distributed under the MIT License. See `LICENSE.txt` for more information.



## Creating Staging Table And Performing Data Recialiation

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



## Loading Data Again To The MySQL

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
