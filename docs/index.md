---
layout: default
---

# PAPER

<div class="hero has-text-centered" id="paper">
<div class="myWrapper" markdown="1" align="left">

**[ScanNeRF: a Scalable Benchmark for Neural Radiance Fields](https://arxiv.org/abs/2211.13762)**

***Luca De Luigi\*, Damiano Bolognini\*, Federico Domeniconi\*, Daniele De Gregorio, Matteo Poggi, Luigi Di Stefano***<br>
[Eyecan.ai](https://www.eyecan.ai/) *\* Equal contribution*

<div style="text-align: justify;">
In this paper, we propose the first-ever real benchmark thought for evaluating Neural Radiance Fields (NeRFs) and, in general, Neural Rendering (NR) frameworks.
We design and implement an effective pipeline for scanning real objects in quantity and effortlessly. Our <b>scan station</b> is built with less than 500$ hardware budget and can collect roughly 4000 images of a scanned object in just 5 minutes.
Such a platform is used to build <b>ScanNeRF</b>, a dataset characterized by several train/val/test splits aimed at benchmarking the performance of modern NeRF methods under different conditions.
Accordingly, we evaluate three cutting-edge NeRF variants on it to highlight their strengths and weaknesses.
The dataset is available on our project page, together with an online benchmark to foster the development of better and better NeRFs.
</div>
<br>

<div class="youtube-container">
<iframe class="youtube-iframe" src="https://www.youtube.com/embed/bX_Cd55xZk8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Cite Us

If you use this dataset in your research, please cite the following paper:

```
@inproceedings{deluigi2023scannerf,
  title={ScanNeRF: a Scalable Benchmark for Neural Radiance Fields},
  author={De Luigi, Luca and Bolognini, Damiano and Domeniconi, Federico and De Gregorio, Daniele and Poggi, Matteo and Di Stefano, Luigi},
  booktitle={Winter Conference on Applications of Computer Vision},
  note={WACV},
  year={2023}
}
```

</div>
</div>


# THE DATASET

<br>

<div class="hero has-text-centered" id="dataset">


<div class="myWrapper" markdown="1" align="center">

## OBJECTS

<div class="myWrapper" markdown="1" align="center" style="overflow-x: scroll;">

|                                                                    |                                                                    |                                                                    |                                                                    |                                                                    |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| **ariplane 1**                                                     | **ariplane 2**                                                     | **brontosaurus**                                                   | **bulldozer 1**                                                    | **bulldozer 2**                                                    |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\airplane1.gif "airplane1")       | ![Alt text](assets\images\objects\airplane2.gif "airplane2")       | ![Alt text](assets\images\objects\brontosaurus.gif "brontosaurus") | ![Alt text](assets\images\objects\bulldozer1.gif "bulldozer1")     | ![Alt text](assets\images\objects\bulldozer2.gif "bulldozer2")     |
| **cheetah**                                                        | **dump truck 1**                                                   | **dump truck 2**                                                   | **elephant**                                                       | **excavator**                                                      |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\cheetah.gif "cheetah")           | ![Alt text](assets\images\objects\dump_truck1.gif "dump_truck1")   | ![Alt text](assets\images\objects\dump_truck2.gif "dump_truck2")   | ![Alt text](assets\images\objects\elephant.gif "elephant")         | ![Alt text](assets\images\objects\excavator.gif "excavator")       |
| **forklift**                                                       | **giraffe**                                                        | **helicopter 1**                                                   | **helicopter 2**                                                   | **lego**                                                           |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\forklift.gif "forklift")         | ![Alt text](assets\images\objects\giraffe.gif "giraffe")           | ![Alt text](assets\images\objects\helicopter1.gif "helicopter1")   | ![Alt text](assets\images\objects\helicopter2.gif "helicopter2")   | ![Alt text](assets\images\objects\lego.gif "lego")                 |
| **lion**                                                           | **plant 2**                                                        | **plant 2**                                                        | **plant3**                                                         | **plant 4**                                                        |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\lion.gif "lion")                 | ![Alt text](assets\images\objects\plant1.gif "plant1")             | ![Alt text](assets\images\objects\plant2.gif "plant2")             | ![Alt text](assets\images\objects\plant3.gif "plant3")             | ![Alt text](assets\images\objects\plant4.gif "plant4")             |
| **plant 5**                                                        | **plant 6**                                                        | **plant 7**                                                        | **plant 8**                                                        | **plant 9**                                                        |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\plant5.gif "plant5")             | ![Alt text](assets\images\objects\plant6.gif "plant6")             | ![Alt text](assets\images\objects\plant7.gif "plant7")             | ![Alt text](assets\images\objects\plant8.gif "plant8")             | ![Alt text](assets\images\objects\plant9.gif "plant9")             |
| **roadroller**                                                     | **shark**                                                          | **spinosaurus**                                                    | **stegosaurus**                                                    | **tiger**                                                          |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\roadroller.gif "roadroller")     | ![Alt text](assets\images\objects\shark.gif "shark")               | ![Alt text](assets\images\objects\spinosaurus.gif "spinosaurus")   | ![Alt text](assets\images\objects\stegosaurus.gif "stegosaurus")   | ![Alt text](assets\images\objects\tiger.gif "tiger")               |
| **tractor**                                                        | **trex**                                                           | **triceratops**                                                    | **truck**                                                          | **zebra**                                                          |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\objects\tractor.gif "tractor")           | ![Alt text](assets\images\objects\trex.gif "trex")                 | ![Alt text](assets\images\objects\triceratops.gif "triceratops")   | ![Alt text](assets\images\objects\truck.gif "truck")               | ![Alt text](assets\images\objects\zebra.gif "zebra")               |

</div>
</div>
<div class="myWrapper" markdown="1" align="center">
<br>

## TRAINING SPLITS

<div class="myWrapper" markdown="1" align="center" style="overflow-x: scroll;">

|                                                                    |                                                                    |                                                                    |                                                                    |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| **Train 1000**                                                     | **Train 500**                                                      | **Train 250**                                                      | **Train 100**                                                      |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\splits\split_1000.jpg "split_1000")      | ![Alt text](assets\images\splits\split_500.jpg "split_500")        | ![Alt text](assets\images\splits\split_250.jpg "split_250")        | ![Alt text](assets\images\splits\split_100.jpg "split_100")        |
| **Train sub-split 0**                                              | **Train sub-split 1**                                              | **Train sub-split 2**                                              | **Train sub-split 3**                                              |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\splits\sub_split_0.jpg "sub_split_0")    | ![Alt text](assets\images\splits\sub_split_1.jpg "sub_split_1")    | ![Alt text](assets\images\splits\sub_split_2.jpg "sub_split_2")    | ![Alt text](assets\images\splits\sub_split_3.jpg "sub_split_3")    |
| **Train sub-split 4**                                              | **Train sub-split 5**                                              | **Train sub-split 6**                                              | **Train sub-split 7**                                              |
| :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: | :----------------------------------------------------------------: |
| ![Alt text](assets\images\splits\sub_split_4.jpg "sub_split_4")    | ![Alt text](assets\images\splits\sub_split_5.jpg "sub_split_5")    | ![Alt text](assets\images\splits\sub_split_6.jpg "sub_split_6")    | ![Alt text](assets\images\splits\sub_split_7.jpg "sub_split_7")    |

</div>
</div>
</div>
<br>

# LEADERBOARDS

<div class="hero" id="leaderboard" markdown="1">

### EVENLY DISTRIBUTED SPLITS

<div class="hero" id="leaderboard" markdown="1">
<div style="overflow-x: scroll;">
<table class="table table-header-rotated">
    <tr>
        <td style=""><div><span>&nbsp;</span></div></td>
        <td style=""><div><span>&nbsp;</span></div></td>
        <!-- <td style="text-align: center; border-left: 1px solid #dbdbdb;"><div><span><b>average</b></span></div></td> -->
        <td style="text-align: center; vertical-align: bottom; height: 110px; white-space: nowrap; padding: 0 !important;"><div style="transform: translate(10px, -10px) rotate(310deg); width: 30px;"><span style="padding: 5px 10px;"><b>average</b></span></div></td>
        <!-- <td style="text-align: center; border-left: 1px solid #dbdbdb; transform-origin: bottom left; transform: translateX(20%) rotate(-45deg);"><b>average</b></td> -->
        {% for object in site.data.objects %}
            <td style="text-align: center; vertical-align: bottom; border-left: none; height: 110px; white-space: nowrap; padding: 0 !important;"><div style="transform: translate(10px, -10px) rotate(310deg); width: 30px;"><span style="padding: 5px 10px;"><b>{{object}}</b></span></div></td>
            <!-- <td style="text-align: center; border-left: none; transform-origin: bottom left; transform: translateX(20%) rotate(-45deg);"><b>{{object}}</b></td> -->
            <!-- <td style="text-align: center; border-left: none; transform-origin: center; transform: rotate(-45deg);"><b>{{object}}</b></td> -->
        {% endfor %}
    </tr>
    {% for method in site.data.leaderboard %}
        <tr>
            <td rowspan="4" style="vertical-align: middle;"><b>{{method.name}}</b></td>
            <td style="white-space: nowrap;"><b>Train 1000</b></td>
            <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_1000_avg}}</td>
            {% for object in site.data.objects %}
                <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_1000[forloop.index0]}}</td>
            {% endfor %}
        </tr>
        <tr>
            <td style="white-space: nowrap;"><b>Train 500</b></td>
            <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_500_avg}}</td>
            {% for object in site.data.objects %}
                <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_500[forloop.index0]}}</td>
            {% endfor %}
        </tr>
        <tr>
            <td style="white-space: nowrap;"><b>Train 250</b></td>
            <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_250_avg}}</td>
            {% for object in site.data.objects %}
                <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_250[forloop.index0]}}</td>
            {% endfor %}
        </tr>
        <tr>
            <td style="white-space: nowrap;"><b>Train 100</b></td>
            <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_100_avg}}</td>
            {% for object in site.data.objects %}
                <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_100[forloop.index0]}}</td>
            {% endfor %}
        </tr>
    {% endfor %}
</table>
</div>

### DENSELY LOCALIZED SUB-SPLITS
<div>
    {% for method in site.data.leaderboard %}
        {% assign min_value = 100 %}
        {% assign max_value = 0 %}
        {% for row in method.sub_splits %}
            {% for el in row %}
                {% assign el_int = el | plus: 0 %}
                {% if el_int < min_value %}
                    {% assign min_value = el_int %}
                {% endif %}
                {% if el_int > max_value %}
                    {% assign max_value = el_int %}
                {% endif %}
            {% endfor %}
        {% endfor %}
        {% assign diff_value = max_value | minus: min_value %}
        <div style="overflow-x: scroll;">
            <div align="center">
                <h4>{{method.name}}</h4>
            </div>
            <table>
                <tr>
                    <!-- <td style="border-bottom: none">&nbsp;</td> -->
                    <td colspan="9" style="text-align: center; border-bottom: none;"><b>Test Split</b></td>
                </tr>
                <tr>
                    <td style="text-align: center;"><b>Train split</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>0</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>1</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>2</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>3</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>4</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>5</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>6</b></td>
                    <td style="text-align: center; border-left: 1px solid #dbdbdb;"><b>7</b></td>
                </tr>
                {% for row in method.sub_splits %}
                    <tr>
                    <td style="text-align: center;"><b>{{forloop.index0}}</b></td>
                    {% for el in row %}
                        {% assign norm_el = el | minus: min_value | divided_by: diff_value | times: 50 %}
                        <td style="text-align: center; border-left: 1px solid #dbdbdb; background-color:hsla(0, 100%, {{100 | minus: norm_el}}%, 0.5);">{{el}}</td>
                    {% endfor %}
                    </tr>
                {% endfor %}
            </table>
        </div>
        <hr>
        <br>
    {% endfor %}
</div>


<br>
<div align="left">
* <b>DVGO</b> has been trained and tested with half resolution images due to memory constraints.
</div>

<br>
<div class="myWrapper" align="left" markdown="1">

## Submit Your Results

Send us your results on the private test set so we can add your method to our leaderboard!

To do so, send an e-mail to **info@eyecan.ai** with subject "Scannerf results submission" and the following info:

- The **name**/s of your method/s.
- A **description** of your method/s.
- A **download link** with your results for every proposed method, with rendered images for every test set sample. We will compute metrics on those images.

Feel free to ask us any questions!

</div>
</div>
