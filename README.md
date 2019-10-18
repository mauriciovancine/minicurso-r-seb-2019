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
15 + 5 especiais

**Ementa** <br>
A disciplina oferecerá os principais conceitos teórico-práticos introdutórios de geoprocessamento aplicado à Ecologia. A parte prática será desenvolvida através de ferramentas na linguagem R e do software QGIS. Serão abordados os seguintes temas: (i) controle de versão, Git e GitHub, (ii) introdução e funcionamento da linguagem R e do software RStudio, (iii) estrutura e manejo de dados na linguagem R, (iv) introdução ao tidyverse, (v) visualização de dados, (vi) estrutura e fonte de dados geoespaciais, (vii) introdução e funcionamento do software QGIS, e (viii) estrutura e manejo de dados geoespaciais na linguagem R. A carga horária total será de 45 horas, onde nos cinco dias iniciais serão ministrados 6 horas teóricas-práticas, num total de 30 horas. As 15 horas restantes serão direcionadas à realização de exercícios práticos, que serão aplicados remotamente como forma de avaliação para compor a nota final da disciplina. Após a realização da disciplina, espera-se que os alunos adquiram conceitos gerais da estrutura e manipulação de dados espaciais, assim como domínio das técnicas e métodos para alcançar autonomia e produzir soluções para suas próprias questões relativas ao geoprocessamento.

---

### Informações aos participantes

**Datas e horários** <br>
Teórico-prático: 30/09 – 04/10 [09:00 h - 12:00 h | 14:00 h - 17:00 h] (30 horas) <br>
Exercícios-atividades assistidas remotamente: 07/09 – 11/09 (15 horas)

**Local** <br>

**Ementa** <br> 
[pdf](https://github.com/mauriciovancine/disciplina-geoprocessamento/blob/master/00_ementa/ementa.pdf)

**Contato** <br>
Para mais informações ou dúvidas, envie e-mail para Maurício Vancine (mauricio.vancine@gmail.com)

---

### Instruções aos participantes

**Hardware** <br>
Será necessário que todos tragam seus próprios notebooks

**Softwares**<br>
R e RStudio <br>

1. Instalar a versão mais recente do [R (3.6.1)](https://www.r-project.org) e [RStudio (1.2.5001)](https://www.rstudio.com) <br>
[Vídeo de instalação do R e do RStudio](https://youtu.be/l1bWvZMNMCM) <br>
[Curso da linguagem R](https://www.youtube.com/playlist?list=PLucm8g_ezqNq0RMHvzZ8M32xhopFhmsr6)

2. Instalar a versão mais estável do [QGIS (3.4 LTR)](https://qgis.org/pt_BR/site) <br>
[Vídeo de instalação do QGIS](https://youtu.be/QjhCkX2sVI4) <br>
[Curso Básico de QGIS](https://www.youtube.com/playlist?list=PLRrETkwtvTrMEeicAyYABdNwPpnzZdw5q) <br>
[Curso de QGIS 3.6 - MasterGIS](https://www.youtube.com/watch?v=anSaq5pbCpk&list=PLjHRAtOKOOLhHyQHUXBCfSqOWHFJZ1Pnf)

#### Linux (Ubuntu e Linux Mint)
```
# r
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu bionic-cran35/" # mint 19 ou ubuntu 18
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu disco-cran35/" # ubuntu 19
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
wget https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.2.1335-amd64.deb
sudo dpkg -i rstudio-1.2.1335-amd64.deb
sudo apt install -fy
rm rstudio-1.2.1335-amd64.deb
```
---
