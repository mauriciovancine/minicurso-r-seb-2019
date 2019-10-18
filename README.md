# Repositório de dados

## 30ª Semana de Estudos da Biologia - UNESP - Rio Claro

## Nome do minicurso: Introdução ao geoprocessamento para Etnobiologia e Conservação da Biodiversidade 

**Ministrante** <br>
Me. Maurício Humberto Vancine

**Monitores** <br>
Helena
Lucas

**Período** <br>
30/09/2019 - 04/10/2019

**Duração** <br>
08 horas

**Vagas** <br>
15 alunos

**Ementa** <br>

---

### Informações aos participantes

**Datas e horários** <br>
Teórico-prático: 30/09 – 04/10 [09:00 h - 12:00 h | 14:00 h - 17:00 h]

**Local** <br>
À definir

**Ementa** <br> 
[pdf]()

**Contato** <br>
Para mais informações ou dúvidas, envie e-mail para Maurício Vancine (mauricio.vancine@gmail.com)

---

### Instruções aos participantes

**Hardware** <br>
Será necessário que todos tragam seus próprios notebooks

**Softwares**<br>
R e RStudio <br>
1. Instalar a versão mais recente do [R (3.6.1)](https://www.r-project.org) <br>
2. [RStudio (1.2.5001)](https://www.rstudio.com) <br>
[Vídeo de instalação do R e do RStudio](https://youtu.be/l1bWvZMNMCM) <br>
[Curso da linguagem R](https://www.youtube.com/playlist?list=PLucm8g_ezqNq0RMHvzZ8M32xhopFhmsr6)


#### Linux (Ubuntu e Linux Mint)
```
# r
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9

sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu disco-cran35/" # ubuntu 19.04
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu cosmic-cran35/" # ubuntu 18.10
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu bionic-cran35/" # ubuntu 18.04 lts ou mint 19.x
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu xenial-cran35/" # ou ubuntu 16.04 lts ou mint 18.x

sudo apt update

sudo apt install -y r-base-core # r
sudo apt install -y r-base-dev # devtools
sudo apt install -y libssl-dev # tidyverse
sudo apt install -y libxml2-dev # tidyverse
sudo apt install -y libcurl4-openssl-dev # tidyverse
sudo apt install -y libgdal-dev # gdal
sudo apt install -y libproj-dev # gdal
sudo apt install -y libudunits2-dev # units

# rstudio
wget https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.2.5001-amd64.deb
sudo dpkg -i rstudio-1.2.5001-amd64.deb
sudo apt install -fy
rm rstudio-1.2.5001-amd64.deb
```
---
