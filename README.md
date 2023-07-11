# FDA-in-Demography
Contents of the short course "FDA in Demography"

Demographic data (population pyramids, mortality and fertility rates, life expectancy, among other) usually depend on calendar year and/or on age. They can be observed (maybe detailed by sex) for one or several countries (or regions, municipalities, or other geographical divisions). Therefore Functional Data Analysis (FDA) is a perfect framework for describing and modeling demographic data: they can have one or two arguments (calendar year and/or age), they can conform functional time series (when depending on age and having one observation per year for one country) and they can present spatial dependency (regions that are close to each other usually have similar demographic dynamics). 

The outline of this short course is as follows:
\begin{itemize}
\item Definition of basic concepts in Demography.
\item Some demographic data repositories.
\item Software resources for analyzing demographic data as functional data.
\item Examples of FDA applications in Demography.
\end{itemize}
I will present examples of methodologies, applications and software developed by R. Hyndman and his research group (\cite{Hyndman_et_al:2013}, \cite{pkg:demography}, \cite{pkg:ftsa})
as well as other where I have participated directly (\cite{ChenDelMull:2017}, \cite{Delicado:2011}).

\bigskip

### Bibliography
- Chen, K., Delicado, P. and Müller, H.-G. (2017). Modelling function-valued stochastic processes, with applications to fertility dynamics. *Journal of the Royal Statistical Society: Series B (Statistical Methodology)*, **79**, 177--196.
- Delicado, P. (2011). Dimensionality reduction when data are density functions. *Computational Statistics and Data Analysis*, **55**, 401--420.
- Hyndman, R.J., Booth, H. and Yasmeen, F. (2013). Coherent mortality forecasting: the product-ratio method with functional time series models. \emph{Demography}, {\bf 50}, 261-–283.
- Hyndman, R.J. (2019). demography: Forecasting Mortality, Fertility, Migration and Population Data. R package version 1.21. https://CRAN.R-project.org/package=demography
- Hyndman, R.J. and Shang, H.L. (2019). ftsa: Functional Time Series Analysis. R package version 5.4. https://CRAN.R-project.org/package=ftsa
