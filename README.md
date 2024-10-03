# star-spec
Access large spectroscopic stellar parameter databases.

The provided Jupyter Notebook accesses the [K2 stellar parameters database](https://ui.adsabs.harvard.edu/abs/2020ApJS..247...28H/abstract) and crossmatches it with the [APOGEE DR17](https://www.sdss4.org/dr17/irspec/), [GALAH DR3](https://www.galah-survey.org/dr3/overview/), and [LAMOST DR9](http://www.lamost.org/dr9/) stellar parameters databases using Gaia DR3 IDs.

The example sets some data quality cuts and extracts stellar temperature, surface gravity, and metallicity from each database. Seek out the spectroscopic database documentation and modify to include/exclude other parameters as you see fit.

If you use this code in your work, please cite the Scaling K2 paper, and the appropriate spectroscopic databases:

**Scaling K2**
```
@ARTICLE{Hardegree-Ullman2020,
       author = {{Hardegree-Ullman}, Kevin K. and {Zink}, Jon K. and {Christiansen}, Jessie L. and {Dressing}, Courtney D. and {Ciardi}, David R. and {Schlieder}, Joshua E.},
        title = "{Scaling K2. I. Revised Parameters for 222,088 K2 Stars and a K2 Planet Radius Valley at 1.9 R$_{{\ensuremath{\oplus}}}$}",
      journal = {\apjs},
     keywords = {Fundamental parameters of stars, Exoplanet systems, Exoplanets, 555, 484, 498, Astrophysics - Solar and Stellar Astrophysics, Astrophysics - Earth and Planetary Astrophysics},
         year = 2020,
        month = mar,
       volume = {247},
       number = {1},
          eid = {28},
        pages = {28},
          doi = {10.3847/1538-4365/ab7230},
archivePrefix = {arXiv},
       eprint = {2001.11511},
 primaryClass = {astro-ph.SR},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2020ApJS..247...28H},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

**APOGEE DR17**

[See citation information here](https://www.sdss4.org/collaboration/citing-sdss/).

**GALAH DR3**
```
@ARTICLE{Buder2021,
       author = {{Buder}, Sven and {Sharma}, Sanjib and {Kos}, Janez and {Amarsi}, Anish M. and {Nordlander}, Thomas and {Lind}, Karin and {Martell}, Sarah L. and {Asplund}, Martin and {Bland-Hawthorn}, Joss and {Casey}, Andrew R. and {de Silva}, Gayandhi M. and {D'Orazi}, Valentina and {Freeman}, Ken C. and {Hayden}, Michael R. and {Lewis}, Geraint F. and {Lin}, Jane and {Schlesinger}, Katharine J. and {Simpson}, Jeffrey D. and {Stello}, Dennis and {Zucker}, Daniel B. and {Zwitter}, Toma{\v{z}} and {Beeson}, Kevin L. and {Buck}, Tobias and {Casagrande}, Luca and {Clark}, Jake T. and {{\v{C}}otar}, Klemen and {da Costa}, Gary S. and {de Grijs}, Richard and {Feuillet}, Diane and {Horner}, Jonathan and {Kafle}, Prajwal R. and {Khanna}, Shourya and {Kobayashi}, Chiaki and {Liu}, Fan and {Montet}, Benjamin T. and {Nandakumar}, Govind and {Nataf}, David M. and {Ness}, Melissa K. and {Spina}, Lorenzo and {Tepper-Garc{\'\i}a}, Thor and {Ting}, Yuan-Sen and {Traven}, Gregor and {Vogrin{\v{c}}i{\v{c}}}, Rok and {Wittenmyer}, Robert A. and {Wyse}, Rosemary F.~G. and {{\v{Z}}erjal}, Maru{\v{s}}a and {Galah Collaboration}},
        title = "{The GALAH+ survey: Third data release}",
      journal = {\mnras},
     keywords = {methods: data analysis, methods: observational, surveys, stars: abundances, stars: fundamental parameters, Astrophysics - Astrophysics of Galaxies, Astrophysics - Solar and Stellar Astrophysics},
         year = 2021,
        month = sep,
       volume = {506},
       number = {1},
        pages = {150-201},
          doi = {10.1093/mnras/stab1242},
archivePrefix = {arXiv},
       eprint = {2011.02505},
 primaryClass = {astro-ph.GA},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2021MNRAS.506..150B},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

**LAMOST DR9**
```
@ARTICLE{Cui2012,
       author = {{Cui}, Xiang-Qun and {Zhao}, Yong-Heng and {Chu}, Yao-Quan and {Li}, Guo-Ping and {Li}, Qi and {Zhang}, Li-Ping and {Su}, Hong-Jun and {Yao}, Zheng-Qiu and {Wang}, Ya-Nan and {Xing}, Xiao-Zheng and {Li}, Xin-Nan and {Zhu}, Yong-Tian and {Wang}, Gang and {Gu}, Bo-Zhong and {Luo}, A. -Li and {Xu}, Xin-Qi and {Zhang}, Zhen-Chao and {Liu}, Gen-Rong and {Zhang}, Hao-Tong and {Yang}, De-Hua and {Cao}, Shu-Yun and {Chen}, Hai-Yuan and {Chen}, Jian-Jun and {Chen}, Kun-Xin and {Chen}, Ying and {Chu}, Jia-Ru and {Feng}, Lei and {Gong}, Xue-Fei and {Hou}, Yong-Hui and {Hu}, Hong-Zhuan and {Hu}, Ning-Sheng and {Hu}, Zhong-Wen and {Jia}, Lei and {Jiang}, Fang-Hua and {Jiang}, Xiang and {Jiang}, Zi-Bo and {Jin}, Ge and {Li}, Ai-Hua and {Li}, Yan and {Li}, Ye-Ping and {Liu}, Guan-Qun and {Liu}, Zhi-Gang and {Lu}, Wen-Zhi and {Mao}, Yin-Dun and {Men}, Li and {Qi}, Yong-Jun and {Qi}, Zhao-Xiang and {Shi}, Huo-Ming and {Tang}, Zheng-Hong and {Tao}, Qing-Sheng and {Wang}, Da-Qi and {Wang}, Dan and {Wang}, Guo-Min and {Wang}, Hai and {Wang}, Jia-Ning and {Wang}, Jian and {Wang}, Jian-Ling and {Wang}, Jian-Ping and {Wang}, Lei and {Wang}, Shu-Qing and {Wang}, You and {Wang}, Yue-Fei and {Xu}, Ling-Zhe and {Xu}, Yan and {Yang}, Shi-Hai and {Yu}, Yong and {Yuan}, Hui and {Yuan}, Xiang-Yan and {Zhai}, Chao and {Zhang}, Jing and {Zhang}, Yan-Xia and {Zhang}, Yong and {Zhao}, Ming and {Zhou}, Fang and {Zhou}, Guo-Hua and {Zhu}, Jie and {Zou}, Si-Cheng},
        title = "{The Large Sky Area Multi-Object Fiber Spectroscopic Telescope (LAMOST)}",
      journal = {Research in Astronomy and Astrophysics},
         year = 2012,
        month = sep,
       volume = {12},
       number = {9},
        pages = {1197-1242},
          doi = {10.1088/1674-4527/12/9/003},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2012RAA....12.1197C},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```
