---
layout: default
---

# PAPER

<div class="hero has-text-centered" id="paper">
<div class="myWrapper" markdown="1" align="left">

**[ScanNeRF: a Scalable Benchmark for Neural Radiance Fields]()**

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
<div style="overflow-x: scroll;">
<table>

    <tr>
        <td style="border-bottom: none">&nbsp;</td>
        {% for method in site.data.leaderboard %}
            <td colspan="4" style="text-align: center; border-bottom: none;"><b>{{method.name}}</b></td>
        {% endfor %}
    </tr>

    <tr>
        <td>&nbsp;</td>
        {% for method in site.data.leaderboard %}
            <td style="border-left: 1px solid #dbdbdb;"><b>Split 1000</b></td>
            <td><b>Split 500</b></td>
            <td><b>Split 250</b></td>
            <td style="border-right: 1px solid #dbdbdb;"><b>Split 100</b></td>
        {% endfor %}
    </tr>

    {% for object in site.data.objects %}
        <tr>
            <td style="border-right: 1px solid #dbdbdb;"><b>{{object}}</b></td>
            {% for method in site.data.leaderboard %}
                <td style="text-align: center; border-left: 1px solid #dbdbdb;">{{method.split_1000[forloop.parentloop.index0]}}</td>
                <td style="text-align: center;">{{method.split_500[forloop.parentloop.index0]}}</td>
                <td style="text-align: center;">{{method.split_250[forloop.parentloop.index0]}}</td>
                <td style="text-align: center; border-right: 1px solid #dbdbdb;">{{method.split_100[forloop.parentloop.index0]}}</td>
            {% endfor %}
        </tr>
    {% endfor %}

</table>
</div>
<br>
<div align="left">
* <b>DVGO</b> has been trained and tested with half resolution images due to memory constraints.
</div>

<br>
<div class="myWrapper" align="left" markdown="1">

</div>
</div>
