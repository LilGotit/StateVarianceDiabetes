<a name="readme-top"></a>

<h3 align="center">Diabetes Variance, by State</h3>

  <p align="center">
    Utilize API calls to gather population data and a diabetes prevalence statistic, clean and merge this data,
    calculate an estimate population of folks diagnosed with diabetes, and create a pivot table and visualizations to accentuate what may be observed.
    <br />
    <a href="https://github.com/LilGotit/StateVarianceDiabetes/">View Demo</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#dependencies">Dependencies</a></li>
    <li><a href="#objectives">Objectives</a></li>
    <li><a href="#data-dictionary">Data Dictionary</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

My initial idea sought to compare sugar and/or corn sales with diagnosed diabetes per state.

After sifting through hundreds of APIs, I came to realize that such a call was a bit overambitious. 
However, I inevitably stumbled upon a way to preserve the spirit of the project: a lovely website with a multitude of legitimate healthcare and government resource datasets.

Not only did I have solid population data, I also gained access to a Diabetes Prevalence statistic for individuals 20 and older.
This gave me the ability to calculate an estimate from specific columns. Most importantly, I really wanted to grow in the visualization department. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Dependencies

Install the dependent packages, if not already acquired, and updated to the latest version:
* requests
  ```sh
  pip install requests
  ```
* pandas
  ```sh
  pip install pandas
  ```
* matplotlib
  ```sh
  pip install matplotlib
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Objectives

- [ ] Read in two datasets from API calls.
- [ ] Cleaning the data, performing a pandas merge, and calculating values based on the new dataset.
- [ ] Make one Pandas pivot table and two Matplotlib plots.
- [ ] Build a custom data dictionary and include it either in your README or as a separate document.
- [ ] Thoroughly annotated Jupyter notebook with a detailed README.md

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Data Dictionary

| Column Name | Description | Source | Datatype |
| ----------- | ----------- | ------ | -------- |
| State       | ----------- | ------ | -------- |
| Population (2020) | ----- | ------ | -------- |
| Diabetes Prevalence | --- | ------ | -------- |
| Diabetes Population Estimate | --- | --- | --- |


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Joshua Beld - [LinkedIn](https://www.linkedin.com/in/joshuabeld/)

Project Link: [https://github.com/LilGotit/StateVarianceDiabetes/](https://github.com/LilGotit/StateVarianceDiabetes/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [Code Louisville - specifically, the mentors and regular contributors in the 2023 Data Analysis 2 cohort](https://codelouisville.org/)
* [Othneil Drew's README template - essential in quickly dispatching a crucial documentation requirement](https://github.com/othneildrew/Best-README-Template/)
* [Geeks For Geeks - my much-needed escape from StackOverflow](https://www.geeksforgeeks.org/)
* [A valuable read on why we need to protect this population](https://www.hrw.org/report/2022/04/12/if-im-out-insulin-im-going-die/united-states-lack-regulation-fuels-crisis)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

[MIT License](https://github.com/LilGotit/StateVarianceDiabetes/blob/main/LICENSE.txt)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
