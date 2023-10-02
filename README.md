<p align="center">
	<img width="200px" src="Anaplan API Live Logo.png">
</p>  
<p align="center">
  <a href="https://www.mit.edu/~amini/LICENSE.md"><img alt="https://www.mit.edu/~amini/LICENSE.md" src="https://img.shields.io/badge/license-MIT-green"></a>
  <a href="https://github.com/EliteEPM/AnaplanAPILive/releases"><img alt="https://github.com/EliteEPM/AnaplanAPILive/releases" src="https://img.shields.io/badge/release-1.0.0-blue.svg"></a>
  <a href="https://mybinder.org/v2/gh/EliteEPM/AnaplanAPILive/v1.0.0?labpath=notebook"><img alt="https://mybinder.org/v2/gh/EliteEPM/AnaplanAPILive/v1.0.0?labpath=notebook" src="https://mybinder.org/badge_logo.svg"></a>
</p>  

# Anaplan API 2.0 Live
Ever wanted to play around with Anaplan APIs and get them to work in your project? Start here!  

Repo includes a Jupyter Notebook in the notebook folder and a Binder Link. The notebook can run all Anaplan APIs published as of September, 2023. The included Python code is easily human readable and requires little foreknowledge  

Click the Launch Binder link to generate a live notebook environment  

<span style="color:red">⚠️ WARNING ⚠️</span>  
This project is only for educational purposes. Elite EPM or Anaplan will not assume any liabilities. Do not enter production data or credentials into the environment. While Binder instances are ephemeral, they are always on shared computing environments. [Review the official Binder Usage guidelines](https://mybinder.readthedocs.io/en/latest/about/user-guidelines.html)

## Why was this created? And what APIs are covered
We created this free resource to help the Anaplan community familiarize themselves with the APIs. Anaplan continually updates and adds more APIs. This makes the platform highly extensible and allows for a lot of automation. The following APIs are covered in this notebook:

|                **API**                	| **Coverage** 	|
|:-------------------------------------:	|:------------:	|
| Integration APIs (Transactional)      	|       ✅      	|
| Integration APIs (Bulk)               	|       ✅      	|
| SCIM APIs                             	|       ❌      	|
| CloudWorks APIs                       	|       ❌      	|
| Application Lifecycle Management APIs 	|       ✅      	|
| Audit APIs                            	|       ❌      	|
| Authentication Service APIs           	|       ✅      	|
| OAuth2.0 APIs                           	|       ✅      	|

## What is Binder?
[Binder](https://mybinder.readthedocs.io/en/latest/using/using.html) creates an ephemeral environment and immediately launches your private instance of the API notebook. Binder is an excellent community resource providing free and shareable computing environments. This project should get your personal Anaplan API sandbox up and running within a minute  

## I don't want to use Binder
That is fine! Just download the latest release and install [Jupyter Lab](https://jupyter.org/install) locally on your computer. The notebook will work exactly the same

## What do I need?  
* Read the official Apiary docs from [Anaplan](https://help.anaplan.com/integration-api-v20-399496b0-d66e-4a84-895a-8d1ffdee2e6b)
* Basic Python knowledge is helpful but not mandatory  
    * What are python comment statements and how to uncomment code
    * What are variables and filling in empty variables
    * What is a web request (GET, POST, PUT)
    * Web Request error and success [codes](https://restfulapi.net/http-status-codes/)
* Jupyter Lab knowledge. [Quick Intro video](https://www.youtube.com/watch?v=jZ952vChhuI)
* What is JSON and how to read JSON
* Access to an Anaplan Workspace and Model, preferably with Workspace Administrator

## Examples

