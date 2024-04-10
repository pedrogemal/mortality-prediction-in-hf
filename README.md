# Mortality prediction in Heart Failure

> This project contains tools and assets needed to run data science experiments using a MIMIC-IV derived subset.

## 🎯 Motivation/Goal

This study aimed to estimate survival time including median time of survival, and to assess the association and impact of covariates to death and survival.

## 📙 Dataset Description

### Data Description

MIMIC (Medical Information Mart for Intensive Care) is a large, freely-available database comprising deidentified health-related data from patients who were admitted to the critical care units of the Beth Israel Deaconess Medical Center.

MIMIC-IV contains data from 2008-2019. The admission vital signs, clinical measurements, and laboratory values were defined as either the first value recorded after or closest to the index CICU admission. Vital signs were recorded every 15 min during the first hour after ICU admission from Metavision bedside monitors. Admission diagnoses were defined as all International Classification of Diseases‐9 diagnostic codes.

## ⚙️ Usage

To be able to run the Notebooks properly, you should have a local `.env` as the example below:

```
GIT_USER = ...
GIT_PAO = ...
```

Please make sure to replate the `...` with your github username and personal access token (PAO), respectively. Keep in mind that this PAO should have read permission to this repository.

This safety measure was needed since the dataset may not have as open access.

As always, `.env` file should be always ignored on commits.

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. 

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## 📝 License

Distributed under the MIT License. See `LICENSE.md` for more information.

<!-- CONTACT -->
## Contact

Pedro Gemal Lanzieri - (https://linkedin.com/pedro-lanzieri)

<p align="right">(<a href="#top">back to top</a>)</p>