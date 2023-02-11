---
layout: page
title:
permalink: /

pubs:

    - title:   "Oysternet: Enhanced oyster detection using simulation"
      author:  "Xiaomin Lin, Nitin J Sanket, Nare Karapetyan, Yiannis Aloimonos"
      journal: "2023 IEEE International Conference on Robotics and Automation (ICRA)"
      url: "https://arxiv.org/pdf/2209.08176.pdf"
      media:
        - name: "Demo Video"
          url:  "https://www.youtube.com/watch?v=QCIsmINfXmA&t=3s&ab_channel=PRGUMD"

    - title:   "SeaDroneSim: Simulation of Aerial Images for Detection of Objects Above Water"
      author:  "Xiaomin Lin, Cheng Liu, Allen Pattillo, Miao Yu, Yiannis Aloimonous"
      journal: "In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision"
      url:     "https://openaccess.thecvf.com/content/WACV2023W/MaCVi/papers/Lin_SeaDroneSim_Simulation_of_Aerial_Images_for_Detection_of_Objects_Above_WACVW_2023_paper.pdf"
      media:
        - name: "Demo Video"
          url:  "https://youtu.be/sljpH1RAtyc"
        - name: "Poster"
          url:  "https://drive.google.com/file/d/128Yfx8gDGtG2-py_1dXKUoKMEPK74F1J/view?usp=share_link"

    - title:   "OysterSim: Underwater Simulation for Enhancing Oyster Reef Monitoring"
      author:  "Xiaomin Lin, Nitesh Jha, Mayank Joshi, Nare Karapetyan, Yiannis Aloimonos, Miao Yu"
      journal: "OCEANS 2022, Hampton Roads, VA, USA, 2022, pp. 1-6, doi: 10.1109/OCEANS47191.2022.9977233."
      url:     "https://arxiv.org/pdf/2209.09395.pdf"
      media:
        - name: "Demo Video"
          url: "https://youtu.be/AKng8L0Vccs"


    - title:   "Discovering Underlying Plans Based on Shallow Models"
      author:  "Hankz Hankui Zhuo, Xiaomin Zha, Subbarao Kambhampati, and Xin Tian"
      journal: "In Proceedings of ACM Transactions on Intelligent Systems and Technology (ACM-TIST) 2019."
      url:     "https://yochan-lab.github.io/papers/files/papers/hankz_tist_19.pdf"
      media:
        - name: "Code"
          url: "https://github.com/XiaominZha/Discovering-Underlying-Plans-Based-on-Shallow-Models"

    - title:   "Explicability as Minimizing Distance from Expected Behavior"
      author:  "Anagha Kulkarni, Xiaomin Zha, Tathagata Chakraborti, Satya Gautam Vadlamudi, Yu Zhang and Subbarao Kambhampati"
      journal: "In Proceedings of International Conference on Autonomous Agents and Multiagent Systems (AAMAS) 2019."
      url:     "https://yochan-lab.github.io/papers/files/papers/anagha-aamas-2019.pdf"
      media:
        - name: "Full Paper"
          url: https://arxiv.org/abs/1611.05497
        - name: "Demo Video"
          url:  "https://youtu.be/iLG-ANQtYms"

---

{% include image.html url="images/photo.png" caption="" max_width="3px" align="right" %}

Xiaomin was born in [Wenzhou](https://en.wikipedia.org/wiki/Wenzhou), China. Xiaomin's robotics journey truly set out when he was an undergrad, worked with [Dr. Temesguen Messay](https://udayton.edu/directory/engineering/electrical_and_computer/kebede_temesguen.php){:target="_blank"}  at  [Motoman Robotics Lab](https://udayton.edu/engineering/research/research-labs/robotics_lab/index.php){:target="_blank"}.

After that, Xiaomin went to University of Maryland- College Park and had a delighted Master life with his advisor [Prof. Gilmer Blankenship](https://mti.umd.edu/clark/faculty/366/Gilmer-L-Blankenship){:target="_blank"}.

Recently, Xiaomin becomes a Ph.D. candidate, working with [Prof. Yiannis Aloimonos](http://users.umiacs.umd.edu/~yiannis/){:target="_blank"} and [Dr. Cornelia Fermüller](https://isr.umd.edu/clark/faculty/1168/Cornelia-Ferm%C3%BCller){:target="_blank"} in the [Perception & Robotics Group](http://prg.cs.umd.edu/){:target="_blank"}, at the University of Maryland, College Park.

Research Interest:

Xiaomin is interested in Cognitive Robotics -- robotics, computer vision, and general Artificial Intelligence. He is currently working on developing novel algorithms for underwater unmanned systems perception.

Teaching Experience:

Spring 2021 ENEE350: Computer Organization <br>
[Fall2020 CMSC 426: Computer Vision](http://prg.cs.umd.edu/cmsc426-fall2020){:target="_blank"} <br>
Spring 2020 ENEE350: Computer Organization <br>
Fall 2019 ENEE303(H): Analog and Digital Electronics <br>
Fall 2019 ENEE408I: Capstone Design Project: Autonomous Control of Interacting Robots <br>
Spring 2019 ENEE350: Computer Organization <br>
Fall 2018 ENEE408I: Capstone Design Project: Autonomous Control of Interacting Robots <br>
Fall 2018 ENEE380: Electromagnetic Theory <br>




Please feel free to contact Xiaomin via [xlin01 at umd dot edu](mailto:xlin01@umd.edu) or [LinkedIn](https://www.linkedin.com/in/xiaomin-lin-42482085/){:target="_blank"}.

<span style="color:red">News!</span>

03/2023: We submiited a paper to  [Maryland Robotics Center Postdoctoral Fellowship](https://robotics.umd.edu/education/postdoctoral-fellowship-program-0) at the Institute for Systems Research (ISR), University of Maryland, 2022-2023.

06/30/2021: Our paper <span style="color:red">[Contrastively Learning Visual Attention as Affordance Cues from Demonstrations for Robotic Grasping](https://arxiv.org/abs/2104.00878){:target="_blank"}</span> is accecped by IROS 2021. Thanks to my collaborators!

04/30/2021: I am awarded the CIDSE Doctoral Fellowship by ASU.  

03/2020 - 08/2020: Worked as a robotics research intern at ABB, Raleigh advised by Dr. Jianjun Wang.

# <a name="publications"></a>Publications

{% for pub in page.pubs %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %}){:target="_blank"}<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}}){:target="_blank"}] {% endfor %}{% endif %}

{% endfor %}
