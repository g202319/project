## <p align="center">Meeting08 - `Formal`</p>

<p align="center">
Date: 2023.11.15 | Secretary: Zhikai Hu
</p>

### Topic

* Progress update
* Discussing the diagrams implementation
* Discussing the realization of AI Cloth partnering

### Participants

* Attendance:
*Qian Zhang* (supervisor), Zheyuan Jiang,  Zhikai Hu, Chenglong Xia, Tan Yee Yang, Elkin Agilroy KRISTAN
* Absence: Xingze Liu[physical issues]

### Meeting Record

* Discussing about the diagrams(sequence diagram, activity diagram)
  * *Addition*
      * basket function: the user can select different clothes and not trying on immediately but adding them to the basket for further try-on
      * Recommend not to store the user information to the database including the user body features and personal image.
      * Accrodingly, we prefer using cameras to get the user image and instead of storing it to the database, we straightly swap it onto the model
* For the software function addition
  * User hsould be able to browsing and filtering
* For AI Recommendation system
  * collaborative filtering recommendation system(not enough data so not ML-based)
* More
  * For prototype,displaying the image is ok, **but** in the UI part of the interim report, you need to specify its working principle
