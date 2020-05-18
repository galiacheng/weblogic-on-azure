# Weblogic on Azure
This repository shows how to deploy a Java EE application to Azure using WebLogic and Linux virtual machines. The repository hosts the demos for this [talk](abstract.md) or materials for [this](lab-abstract.md) lab. The prerequistes for the lab are [here](prerequisites.md). The associated slide deck is [here](https://aka.ms/weblogic-on-azure-deck).

The basic Java EE application used throughout is in the [javaee](/javaee) folder. You should set up and explore this application on your local machine.

The scenarios demonstrated include:

* Deploying a Java EE application on Azure using a simple instance of WebLogic using a marketplace solution. The [simple](/simple) folder shows how this is done.
* Deploying a Java EE application on Azure into a WebLogic cluster using a marketplace solution. The [cluster](/cluster) folder shows how this is done.

We recommend doing the samples in the following order, but the text is
written with sufficient redundancy so that you can do them in any
order. Just be advised that you may have to skip over sections that
you already completed if you jump around in this way.

* [javaee](/javaee)
* [simple](/simple)
* [cluster](/cluster)

The demos use Java EE 7, Maven, Eclipse and PostgreSQL.
