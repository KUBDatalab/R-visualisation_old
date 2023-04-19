---
layout: page
title: Setup
---
## Setup instructions

If you do not have R and Rstudio installed, follow the instructions under the
heading `I dont have R and RStudio installed`, and return to the next part of this page
afterwards.

### I allready have R and RStudio installed!

In that case all you need to do is the following:

Make sure you have `tidyverse` installed:

~~~
install.packages("tidyverse")
~~~
{: .language-r}

Check that the package is installed and work:

~~~
library(tidyverse)
~~~
{: .language-r}

### I'm not sure R and RStudio is updated!

It is a good idea to keep both programs updated!

### Windows

* Open RStudio, and click on "Help" > "Check for updates". If a new version is
	available, quit RStudio, and download the latest version for RStudio.
* To check which version of R you are using, start RStudio and the first thing
  that appears in the console indicates the version of R you are
  running. Alternatively, you can type `sessionInfo()`, which will also display
  which version of R you are running. Go on
  the [CRAN website](https://cran.r-project.org/bin/windows/base/) and check
  whether a more recent version is available. If so, please download and install
  it. You can [check here](https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f) for
  more information on how to remove old versions from your system if you wish to do so.

### macOS

* Open RStudio, and click on "Help" > "Check for updates". If a new version is
	available, quit RStudio, and download the latest version for RStudio.
* To check the version of R you are using, start RStudio and the first thing
  that appears on the terminal indicates the version of R you are running. Alternatively, you can type `sessionInfo()`, which will also display which version of R you are running. Go on
  the [CRAN website](https://cran.r-project.org/bin/macosx/) and check
  whether a more recent version is available. If so, please download and install
  it. In any case, make sure you have at least R 3.3.
  


## I dont have R and RStudio installed

> ## Where to install?
>
> Please do NOT install R and RStudio on Onedrive or other clouddrives.
> R will work but you will not be able to install the extensions to R
> that you will need in this course!
>
{: .caution}

**R** and **RStudio** are separate downloads and installations. R is the
underlying statistical computing environment, but using R alone is no
fun. RStudio is a graphical integrated development environment (IDE) that makes
using R much easier and more interactive. You need to install R before you
install RStudio. Once installed, because RStudio is an IDE, RStudio will run R in 
the background.  You do not need to run it separately. 

After installing both programs, 
you will need to install the **`tidyverse`** package from within RStudio. The 
**`tidyverse`** package is a powerful collection of data science tools within **R** 
see the [**`tidyverse`** website](https://tidyverse.tidyverse.org) for more details. 
Follow the instructions below for your operating system, and then follow the 
instructions to install **`tidyverse`**.


### Windows

* Download R from
  the [CRAN website](http://cran.r-project.org/bin/windows/base/release.htm).
* Run the `.exe` file that was just downloaded.
* Go to the [RStudio download page](https://posit.co/download/rstudio-desktop/#download).
* The site will attempt to guess the correct version depending on your computer.
  If the guess is wrong, find the correct version at the bottom of the page
* Double click the file to install it.
* Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.

Now return to the top of this page and finish the instructions under 
"I allready have R and RStudio installed!"

### macOS

* Download R from
  the [CRAN website](http://cran.r-project.org/bin/macosx/).
* Select the `.pkg` file for the latest R version.
* Double click on the downloaded file to install R.
* It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed
  by some packages).
* Go to the [RStudio download page](https://posit.co/download/rstudio-desktop/#download).
* The site will attempt to guess the correct version depending on your computer.
  If the guess is wrong, find the correct version at the bottom of the page
* Double click the file to install it.
* Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.

Now return to the top of this page and finish the instructions under 
"I allready have R and RStudio installed!"

### Linux

* Follow the instructions for your distribution
  from [CRAN](https://cloud.r-project.org/bin/linux), they provide information
  to get the most recent version of R for common distributions. For most
  distributions, you could use your package manager (e.g., for Debian/Ubuntu run
  `sudo apt-get install r-base`, and for Fedora `sudo yum install R`), but we
  don't recommend this approach as the versions provided by this approach are
  usually out of date. In any case, make sure you have at least R 3.3.
* Go to the [RStudio download page](https://posit.co/download/rstudio-desktop/#download).
* The site will attempt to guess the correct version depending on your computer.
  If the guess is wrong, find the correct version at the bottom of the page
* Double click the file to install it.
* Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.

Now return to the top of this page and finish the instructions under 
"I allready have R and RStudio installed!"

### Online

The company behind RStudio offers a free cloudbased instance of RStudio at 
[Posit Cloud](https://posit.cloud/). 
where you will be able to run R and RStudio in your browser. 
Sign up with your Google/Gmail account if you have one, or with any other email.

The free version of Posit Cloud places limitations on the number of projects you
can work on, and the amount of memory and processing power you can access. 

For the purposes of this course, Posit Cloud is a good alternative to installing R and RStudio on your own computer.
