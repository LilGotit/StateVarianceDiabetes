<a name="readme-top"></a>

<h3 align="center">Diabetes Variance, by State</h3>

  <p align="center">
    Utilize APIs to gather population and diabetes prevalence, clean and merge this data, calculate an estimated diabetic population, and create a pivot table with visualizations for these findings.
    <br />
    <br />
    <a href="https://github.com/LilGotit/StateVarianceDiabetes/blob/main/StateVarianceDiabetes.ipynb">View Jupyter Notebook Demonstration</a>
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

My initial idea sought to compare sugar and/or corn sales with the number of diagnosed diabetics per state.

After sifting through hundreds of APIs, I came to realize that such a call was a bit overambitious. 
However, I inevitably stumbled upon a way to preserve the spirit of the project: a lovely website with a multitude of legitimate healthcare and government resource datasets.

Not only did I have solid population data, I also gained access to a Diabetes Prevalence statistic for individuals 20 and older.
This gave me the ability to calculate an estimate from specific columns.

Most importantly, I sought growth in the visualization department, to create a more refined plot. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Dependencies

Install the dependent packages from the requirements.txt file:
 
  ```sh
  pip install -r requirements.txt
  ```
Individually, if not already acquired, and updated to the latest version:
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

- [ ] Read in two datasets from API calls
- [ ] Clean the data, perform a pandas merge, and calculate values based on the new dataset.
- [ ] Make one Pandas pivot table and one Matplotlib plot
- [ ] Build a custom data dictionary, and include it either in your README or as a separate document.
- [ ] Thoroughly annotated Jupyter notebook with a detailed README.md

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Data Dictionary

| Column Name | Description | Source | Datatype |
| ----------- | ----------- | ------ | -------- |
| State       | Geological grouping with its own government | [Census Bureau](https://census.gov/) & [County Health Rankings](http://countyhealthrankings.org) | object |
| Population (2020) | Approximate population count, in 2020 | [Census Bureau](https://census.gov/) | int64 |
| Diabetes Prevalence | Statistic calculated by County Health Rankings | [County Health Rankings](http://countyhealthrankings.org) | float64 |
| Diabetic Population Estimate | Estimated diabetic population, per area | Population multiplied by non-adult reporting factor multiplied by the Diabetes Prevalence Statistic | int32 |


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Joshua Beld - [LinkedIn](https://www.linkedin.com/in/joshuabeld/)

Project Link: [https://github.com/LilGotit/StateVarianceDiabetes/](https://github.com/LilGotit/StateVarianceDiabetes/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [A valuable read on the need to protect this population](https://www.hrw.org/report/2022/04/12/if-im-out-insulin-im-going-die/united-states-lack-regulation-fuels-crisis)
* [Code Louisville - specifically, the mentors and regular contributors in the 2023 Data Analysis 2 cohort](https://codelouisville.org/)
* [DataUSA.io - Invaluable resource for United States datasets](https://datausa.io/)
* [Othneil Drew's README template - essential in quickly dispatching a crucial documentation requirement](https://github.com/othneildrew/Best-README-Template/)
* [Geeks For Geeks - a much-needed escape from StackOverflow](https://www.geeksforgeeks.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

[MIT License](https://github.com/LilGotit/StateVarianceDiabetes/blob/main/LICENSE.txt)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
