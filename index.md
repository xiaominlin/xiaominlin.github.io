---
layout: page
title:
permalink: /

pubs:
    - title:   "Simulation Based Oyster Detection"
      author:  "Xiaomin Lin, Allen Pattillo, Yiannis Aloimonos"
      journal: "Aquaculture America 2023, New Orleans, Louisiana USA"
      url: "https://github.com/xiaominlin/xiaominlin.github.io/blob/main/files/Aquaculture_American_2023_Simulation_based_Oyster_detection-compressed.pdf"
      media:
        - name: "Abstract"
          url:  "https://github.com/xiaominlin/xiaominlin.github.io/blob/main/files/Aquaculture_American_2023_Simulation_based_Oyster_detection-compressed.pdf"  

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


    - title:   "Following instructions by imagining and reaching visual goals"
      author:  "John Kanu, Eadom Dessalene, Xiaomin Lin, Cornelia Fermuller, Yiannis Aloimonos"
      journal: ""
      url:     "https://arxiv.org/pdf/2001.09373.pdf"
      media:
        - name: "Paper"
          url: "https://arxiv.org/pdf/2001.09373.pdf"

---

{% include image.html url="images/photo.png" caption="" max_width="3px" align="right" %}

Xiaomin was born in [Wenzhou](https://en.wikipedia.org/wiki/Wenzhou), China. Xiaomin's robotics journey truly set out when he was an undergrad, worked with [Dr. Temesguen Messay](https://udayton.edu/directory/engineering/electrical_and_computer/kebede_temesguen.php){:target="_blank"}  at  [Motoman Robotics Lab](https://udayton.edu/engineering/research/research-labs/robotics_lab/index.php){:target="_blank"}.

After that, Xiaomin went to University of Maryland- College Park and had a delighted Master life with his advisor [Prof. Gilmer Blankenship](https://mti.umd.edu/clark/faculty/366/Gilmer-L-Blankenship){:target="_blank"}.

Recently, Xiaomin becomes a Ph.D. candidate, working with [Prof. Yiannis Aloimonos](http://users.umiacs.umd.edu/~yiannis/){:target="_blank"} and [Dr. Cornelia Fermüller](https://isr.umd.edu/clark/faculty/1168/Cornelia-Ferm%C3%BCller){:target="_blank"} in the [Perception & Robotics Group](http://prg.cs.umd.edu/){:target="_blank"}, at the University of Maryland, College Park.

Research Interest:

Xiaomin is interested in Cognitive Robotics -- robotics, computer vision, and general Artificial Intelligence. He is currently working on developing novel algorithms for underwater unmanned systems perception.

Teaching Experience:

ENEE350: Computer Organization (Spring 2021)<br>
[CMSC 426: Computer Vision](http://prg.cs.umd.edu/cmsc426-fall2020){:target="_blank"} (Fall2020)<br>
ENEE350: Computer Organization (Spring 2020)<br>
ENEE303(H): Analog and Digital Electronics (Fall 2019)<br>
ENEE408I: Capstone Design Project: Autonomous Control of Interacting Robots (Fall 2019)<br>
 ENEE350: Computer Organization (Spring 2019)<br>
ENEE408I: Capstone Design Project: Autonomous Control of Interacting Robots (Fall 2018)<br>
ENEE380: Electromagnetic Theory (Fall 2018) <br>




Please feel free to contact Xiaomin via [xlin01 at umd dot edu](mailto:xlin01@umd.edu) or [LinkedIn](https://www.linkedin.com/in/xiaomin-lin-42482085/){:target="_blank"}.

 <font size="+3"><span style="color:red">News!</span></font>
02/26/2023: We are going to present our [Simulation Based Oyster Detection](https://github.com/xiaominlin/xiaominlin.github.io/blob/main/files/Aquaculture_American_2023_Simulation_based_Oyster_detection-compressed.pdf) at AQUACULTURE AMERICA 2023, New Orleans, Louisiana USA

02/10/2023: We submitted a paper to  [Robotics: Science and Systems Jul 10 – Jul 14, 2023, Daegu, Republic of Koreap](https://roboticsconference.org/). Details of the paper will be available soon.

1/16/2023: Our paper <span style="color:red">[Oysternet: Enhanced oyster detection using simulation](https://arxiv.org/pdf/2209.08176.pdf){:target="_blank"}</span> is accepted by ICRA 2023. Thanks to my collaborators!

11/15/202: Our paper <span style="color:red">[SeaDroneSim: Simulation of Aerial Images for Detection of Objects Above Water](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/papers/Lin_SeaDroneSim_Simulation_of_Aerial_Images_for_Detection_of_Objects_Above_WACVW_2023_paper.pdf){:target="_blank"}</span> is accepted by WACV 2023. Thanks to my collaborators!

# <a name="publications"></a>Publications

{% for pub in page.pubs %}
[**{{pub.title}}**]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %}){:target="_blank"}<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.media %}<br />Media: {% for article in pub.media %}[[{{article.name}}]({{article.url}}){:target="_blank"}] {% endfor %}{% endif %}

{% endfor %}
