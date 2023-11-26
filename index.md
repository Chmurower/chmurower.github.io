---
layout: default
---

# Welcome to Chmurower webpage!
_You can learn about or mission here!_

* * *

**Who?**

Chmurower is a crew of IT students who met on [WSB Merito University](https://www.merito.pl/wroclaw/)

As a guys, who during the years of studying, did manage to get
to know each other quite well and learned how to efficiently
cooperate, the choice to form Chmurower was almost natural.
"Group Project" course in WSB Merito is to teach us how to
colaborate in professional environment, with mentorship 
from [Wojciech Barczynski](https://github.com/wojciech11/).

**Why?**

Since we all love cycling in all form, and when travelling
abroad or being around local bike parks, we've often encountered
problems with organization of information, rental management
applications not working, or being hard to handle for employees
of bike rental places.

We've decided that we can make a difference, knowing our ways
around bikes, what people want from them, how to handle service 
and also being deep in the information technology industry,
it was only logical to develop this kind of application.

**What?**

With the above assumptions in mind, we've decided to develop
an easy to deploy, easy to use and easily servicable cloud
application called "Bike Rental".
App is designed to be deployed on private as well as public cloud,
with ~~all~~ some of the necessary scripts needed for seamless
integration.

(at this moment, implementation is ready for private cloud
 and for Azure App Service)

**How?**

Since before starting the project we've already knew some
technologies that could serve as tools for this project development,
we've decided to use ASP.NET Core backend with natural choice of Blazor
as frontend. Database is handled by MySQL.
Initially developed as an app running on localhost by [Lukas](https://github.com/LukasZlocki)
with experience in C# (hence the ASP.NET and Blazor choice), it was,
as soon as possible, contenerized and set up to be run with Docker by
[Jacek](https://github.com/Jacek-Kapral) with the idea of possibility 
of seamless and easy deployment in private cloud or bare metal server.
Finally, [Pawel](https://github.com/PZ-wsb) worked on the integration
with Azure App Service, and is still working, focused on AWS and GCP
integration, with different public cloud environments on the back seat,
waiting for their turns.

Final step is to use Terraform for configuration of host environment
in cloud, with the idea of IaC in mind.




[Technologies used and people involved](./subpage.html).

