# tibero-docker-swonly
Docker Image - Tibero Software - No Database Created.

![Tibero logo](https://www.dimensigon.com/wp-content/uploads/2020/04/Logo-DB-Standard300-Tibero.png)

### Container Description

This container holds Tibero Software for testing. No Database is created.

If you wish to create a default database, use [Tibero Ready-to-Go Container](https://hub.docker.com/repository/docker/dimensigon/tibero).

If you wish to create your own database, this is your container.

You will need to execute as root the following statement before starting with the DB Creation.
tctl check $TB_HOME


### Description

Tibero Database is a RDBMS database that has a worldwide growing position as well in Europe. In Asia and especially in South Korea where it has a dominant market share. It has been promoted by the South Korean Government to get a safer data engine against cyberattacks and to be technology independent.

Tibero was built for compatibility with Oracle Database and IBM DB2 Database at the same time. PSM is a built-in language that shares package names with PL/SQL.

Oracle DBAs and DB Developers find Tibero interesting because it shares administration concepts and enable developers to port their code without changes in 97% of the cases. Companies that adopt Tibero pursue to keep 1 code branch that works in 2 different engines at the same time, Oracle and Tibero.

Tibero simplifies the terms of licensing and it is often used as a Cloud Strategy because of the wide number of features available with different cloud providers and the added-value it brings to the applications.

Tibero Database is a proven RDBMS that stands versus Oracle Database or Exadata in terms of performance, scalability, flexibility and security at competitive cost versus Open-Source commercial Ecosystem vendors. 

### Tibero Documentation

[Link](https://technet.tmaxsoft.com/upload/download/online/tibero/pver-20150504-000002/index.html)

- Developers: Tibero tbPSM Reference Guide (PSM is the most similar language to PL/SQL
- DBAs: Tibero Administrator's Guide

[Do you need a schema instead of a Docker container?](https://store.dimensigon.com/plsqlaas-sqlaas) Try the Forever Free Developer service.

### Client and Interfaces

If you need to use GUIs to program, [here](https://store.dimensigon.com/accessing-you-trial-sqlaas) are the instructions on how to configure them.

JDBC Driver has a direct download in the link above. Inside the container you can find all JDBC Drivers in $TB_HOME/client/lib/jar directory.

### TmaxSoft Official Website

Do you want to create your own machine, register in [support.tmaxsoft.com](https://support.tmaxsoft.com) and claim your own trial license.

It lasts for 6 months for each hostname required. You can require the same hostname multiple times.

The license inside the container is not meant for distribution, sale or resale. All rights are reserved to Dimensigon.



## For Support

This machine is for testing only. Community Support is at [support.tmaxsoft.com](https://support.tmaxsoft.com).

Feel free to reach us at [Dimensigon](https://www.dimensigon.com) for any questions.


#### DISCLAIMER

Copyright (c) 2018-, KnowTrade and its affiliates, All rights reserved.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS 'AS IS'
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE."

