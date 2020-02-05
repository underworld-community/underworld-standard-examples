<table><tr><td><img src='./raytay_init.png'></td><td><img src='./raytay.png'></td></tr></table>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/underworld-community/template-project/master)

About
-----
**_Please replace the following with information about your own repository._**

Welcome! This is a template git repository for creating REPRODUCIBLE Underworld code based projects.

REPRODUCIBLE because this project:
1. Is stored in a git repository.
2. Uses a Dockerfile to recreate the exact project environment.

The two features above enable the project to take advantage of software engineering and open source principles, such as:
_version control_, _reproducible environments_, _collaboration_ (Pull Requests, Binderhub), _continuous integration_. 

(See https://the-turing-way.netlify.com/, for a general introduction to these principle. N.B. it is data-science focussed)  

You can use this repository as a GitHub template to start a new repository of your own that matches the requirements of the underworld-community. To get started, hit the "Use this template" button above. See this [quick start guide]( https://github.com/underworld-community/template-project/wiki/Quick-start) for more information.


Files
-----
**_Please give a quick overview of purpose of the model files/directories included in this repo._**
**_Note that while light data files are fine,  heavy data should not be included in your repository._**

File | Purpose
--- | ---
`RayTay.ipynb` | A simple Rayleigh Taylor notebook. 
`VrmsCaseA.txt`| Expected results data file. 
`raytay.png` | Image file.
`raytay_init.png` | Initial image file.

Tests
-----
**_Please specify how your repository is tested for correctness._**
**_Tests are not required for `laboratory` tagged repositories, although still encouraged._**
**_All other repositories must include a test._**

The attained peak VRMs time is tested against an expected value. If it is outside a given tolerance, an exception is raised.

Parallel Safe
-------------
**_Please specify if your model will operate in parallel, and any caveats._**

Yes, test result should be obtained in both serial and parallel operation.

Check-list
----------
- [ ] (Required) Have you replaced the above sections with your own content? 
- [ ] (Required) Have you updated the Dockerfile to point to your required UW/UWG version? 
- [ ] (Required) Have you included a working Binder badge/link so people can easily run your model?
                 You probably only need to replace `template-project` with your repo name. 
- [ ] (Optional) Have you included an appropriate image for your model? 
