# Multi-Object-Tracking-Paper-List

Multi-object tracking is a deeply explored but not successfully solved computer vision task. This filed needs more open sources and more standard evaluation metrics. Opening source code is not the characteristic for this field（maybe the large number of parameters waited to be tuned)......  This is a paper list for multi-object-tracking.

[![img](https://github.com/ifzhang/FairMOT/raw/master/assets/MOT15.gif)](https://github.com/ifzhang/FairMOT/blob/master/assets/MOT15.gif) [![img](https://github.com/ifzhang/FairMOT/raw/master/assets/MOT16.gif)](https://github.com/ifzhang/FairMOT/blob/master/assets/MOT16.gif) [![img](https://github.com/ifzhang/FairMOT/raw/master/assets/MOT17.gif)](https://github.com/ifzhang/FairMOT/blob/master/assets/MOT17.gif) [![img](https://github.com/ifzhang/FairMOT/raw/master/assets/MOT20.gif)](https://github.com/ifzhang/FairMOT/blob/master/assets/MOT20.gif)

<table class="center">
   </font>
<font size="1" face="Courier New" >
   <tr>
      <td rowspan="2";><b>Conf.<b></td>
      <td rowspan="2"><b>Trackers<b></td>
      <td><b>MOT15<b></td>
      <td><b>MOT16<b></td>
      <td><b>MOT17<b></td>
      <td><b>MOT20<b></td>
      <td><b>KITTI<b></td>
      <td><b>UA-DETRAC<b></td>
      <td><b>BDD100K<b></td>
      <td><b>Waymo<b></td>
   </tr>
   <tr>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/MOTP<sup><b></td>
      <td><font size="1"> <b><sup>PR-MOTA<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/MOTP<sup><b></td>
      <td><font size="1"> <b><sup>MOTA<sup><b></td>
   </tr>
   <tr>
      <td rowspan="9"><b>CVPR2021<b></td>
      <td><b><a href="https://arxiv.org/pdf/2101.12159.pdf">DAM-LSTM</a><b></td>
      <td>-</td>
      <td><sub><b><i>49.9/52.5</i></b><sub></td>
      <td><sub><b><i>53.6/55.8</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2103.07889.pdf">LPC_MOT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub>59.0/66.8<sub></td>
      <td><sub>56.3/62.5<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2104.03541.pdf">CorrTracker</a><b></td>
      <td><sub><b><i>62.3/65.7（*）</i></b><sub></td>
      <td><sub><b><i>76.6/74.3（*）</i></b><sub></td>
      <td><sub><b><i>76.5/73.6（*）</i></b><sub></td>
      <td><sub><b><i>65.2/69.1（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2104.00380.pdf">TADAM</a><b></td>
      <td>-</td>
      <td><sub><b><i>59.1/59.5</i></b><sub></td>
      <td><sub><b><i>59.7/58.7</i></b><sub></td>
      <td><sub><b><i>56.6/51.6</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2012.02337.pdf">ArTIST</a><b></td>
      <td>-</td>
      <td><sub><b><i>63.0/61.9</i></b><sub></td>
      <td><sub><b><i>62.3/59.7</i></b><sub></td>
      <td><sub><b><i>53.6/51.0</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2006.06664.pdf">Qdtrack</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>64.6/65.1</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>64.3/-</i></b><sub></td>
      <td><sub><b><i>51.18</i></b><sub></td>
   </tr>
   <tr>
      <td><b><a href="https://www.amazon.science/publications/siammot-siamese-multi-object-tracking">SiamMOT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>65.9/63.3</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2103.08808.pdf">TraDeS</a><b></td>
      <td>-</td>
      <td><sub><b><i>70.1/64.7（*）</i></b><sub></td>
      <td><sub><b><i>69.1/63.9（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/abs/2103.16178.pdf">GMTracker</a><b></td>
      <td>-</td>
      <td><sub>68.7/65.0<sub></td>
      <td><sub>70.6/66.2<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>

​        
   <tr>
​      <td rowspan="4"><b>ECCV20<b></td>
​      <td><b><a href="https://arxiv.org/pdf/2007.14557v1.pdf">CTracker</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>67.6/57.2（*）</i></b><sub></td>
​      <td><sub><b><i>66.6/57.4（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1909.12605.pdf">JDE</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>64.4/55.8（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2004.01177.pdf">CenterTrack</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>61.5/59.6
​       67.8/64.7（*）</i></b><sub></td>
​      <td>-</td>
​      <td><sub><b><i>89.44/85.0（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690613.pdf">DMM-NET</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>12.2</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="8"><b>CVPR20<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1906.06618v2.pdf">DeepMOT</a><b></td>
​      <td>-</td>
​      <td><sub>54.8/53.4<sub></td>
​      <td><sub>53.7/53.8<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr> 
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1912.07515.pdf">MPNTrack</a><b></td>
​      <td><sub>51.5/58.6<sub></td>
​      <td><sub>58.6/61.7<sub></td>
​      <td><sub>58.8/61.7<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>    
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2006.07327.pdf">GNN3DMOT</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub>82.24/84.05<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr> 
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2003.11291.pdf">UMA</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>50.5/52.8</i></b><sub></td>
​      <td><sub><b><i>53.1/54.4</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1912.02096.pdf">MOTSNet</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>58.2/84.0（*）</i></b><sub></td>
​      <td>-</td>
   </tr>     
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2004.07472v1.pdf">SQE</a><b></td>
​      <td>-</td>
​      <td><sub>-/68.3<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr> 
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2003.13870.pdf">RetinaTrack</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>39.19/-（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>44.92（*）</i></b><sub></td>
   </tr> 
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Pang_TubeTK_Adopting_Tubes_to_Track_Multi-Object_in_a_One-Step_Training_CVPR_2020_paper.pdf">TubeTK</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>64.0/59.4（*）</i></b><sub></td>
​      <td><sub><b><i>63.0/58.6（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>     
   <tr>
​      <td rowspan="1"><b>AAAI20<b></td>
​      <td><b><a href="https://aaai.org/ojs/index.php/AAAI/article/view/6694/6548">DASOT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>46.1/49.4</i></b><sub></td>
​      <td><sub><b><i>48.0/51.3</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr> 
   <tr>
​      <td rowspan="1"><b>ICML20<b></td>
​      <td><b><a href="https://arxiv.org/pdf/2006.14550.pdf">Lif_T</a><b></td>
​      <td><sub>52.5/60.0<sub></td>
​      <td><sub>61.3/64.7<sub></td>
​      <td><sub>60.5/65.6<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>   
   <tr>
​      <td rowspan="1"><b>IJCAI20<b></td>
​      <td><b><a href="https://www.ijcai.org/Proceedings/2020/0074.pdf">GSM_Trackor</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>57.0/58.2</i></b><sub></td>
​      <td><sub><b><i>56.4/57.8</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="5"><b>ICCV19<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1903.05625.pdf">Tracktor++</a><b></td>
​      <td><sub><b><i>44.1/46.7（*）</i></b><sub></td>
​      <td><sub><b><i>54.4/52.5（*）</i></b><sub></td>
​      <td><sub><b><i>53.5/52.3（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1904.11489.pdf">STRN</a><b></td>
​      <td><sub><b><i>38.1/46.6</i></b><sub></td>
​      <td><sub><b><i>48.5/53.9</i></b><sub></td>
​      <td><sub><b><i>50.9/56.5</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Chu_FAMNet_Joint_Learning_of_Feature_Affinity_and_Multi-Dimensional_Assignment_for_ICCV_2019_paper.pdf">FAMNet</a><b></td>
​      <td><sub><b><i>40.6/41.4</i></b><sub></td>
​      <td>-</td>
​      <td><sub><b><i>52.0/48.7</i></b><sub></td>
​      <td>-</td>
​      <td><sub><b><i>77.1/78.8</i></b><sub></td>
​      <td><sub><b><i>19.8（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
   </tr> 
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1909.03850.pdf">mmMOT</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>84.77/85.21</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1811.10742.pdf">3DT</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>84.52/85.64</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>CVPR19<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8954391">SAS</a><b></td>
​      <td><sub>22.2/27.1<sub></td>
​      <td>-</td>
​      <td><sub>44.2/57.2<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>CVPRW19<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9025639">JBNOT</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>52.6/50.8</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>AAAI19<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1812.03621.pdf">LNUH</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>47.5/43.6</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>IV19<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1905.02843.pdf">FANTrack</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>77.72/82.32</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="3"><b>ECCV18<b></td>
​      <td><b><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Ji_Zhu_Online_Multi-Object_Tracking_ECCV_2018_paper.pdf">DMAN</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>46.1/54.8</i></b><sub></td>
​      <td><sub><b><i>48.2/55.7</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Collaborative_Deep_Reinforcement_ECCV_2018_paper.pdf">C-DRL</a><b></td>
​      <td><sub><b><i>37.1/-</i></b><sub></td>
​      <td><sub><b><i>47.3/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_ECCV_2018/papers/Chanho_Kim_Multi-object_Tracking_with_ECCV_2018_paper.pdf">MHT-bLSTM</a><b></td>
​      <td>-</td>
​      <td><sub>42.1/47.8<sub></td>
​      <td><sub>47.5/51.9<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="2"><b>CVPRW18<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1705.08314v4.pdf">FWT</a><b></td>
​      <td>-</td>
​      <td><sub>47.8/47.8<sub></td>
​      <td><sub>51.3/47.6<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8575325">MOT_LSTM</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>62.6/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="2"><b>TPAMI18<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8493320">CCC</a><b></td>
​      <td><sub>35.6/45.1<sub></td>
​      <td><sub>47.1/52.3<sub></td>
​      <td><sub>51.2/54.5<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8766896">DAN</a><b></td>
​      <td><sub><b><i>38.3/45.6</i></b><sub></td>
​      <td>-</td>
​      <td><sub><b><i>52.4/49.5</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="2"><b>ICPR18<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8545450">HOGM</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>64.8/73.5(*)</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1802.09298.pdf">BeyondPixels</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub><b><i>84.24/85.73</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>ACM18<b></td>
​      <td><b><a href="https://dl.acm.org/doi/pdf/10.1145/3343031.3350853">TNT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>49.2/56.1</i></b><sub></td>
​      <td><sub><b><i>51.9/58.0</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>ICME18<b></td>
​      <td><b><a href="https://arxiv.org/abs/1809.04427.pdf">MOTDT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>47.6/50.9</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="2"><b>ICCV17<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1701.01909.pdf">AMIR</a><b></td>
​      <td><sub><b><i>37.6/-</i></b><sub></td>
​      <td><sub><b><i>47.2/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_ICCV_2017/papers/Chu_Online_Multi-Object_Tracking_ICCV_2017_paper.pdf">STAM</a><b></td>
​      <td><sub><b><i>34.3/-</i></b><sub></td>
​      <td><sub><b><i>46.0/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="3"><b>CVPR17<b></td>
​      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Tang_Multiple_People_Tracking_CVPR_2017_paper.pdf">LMP</a><b></td>
​      <td>-</td>
​      <td><sub>48.8/-<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Son_Multi-Object_Tracking_With_CVPR_2017_paper.pdf">Quad-CNN</a><b></td>
​      <td><sub>33.8/-<sub></td>
​      <td><sub>44.1/-<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Schulter_Deep_Network_Flow_CVPR_2017_paper.pdf">DNF</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub>67.36/78.79<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>TPAMI17<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7893777">CDA_DDALpb</a><b></td>
​      <td><sub><b><i>32.8/-
​                     51.3/-(*)</i></b><sub></td>
​      <td><sub><b><i>43.9/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="1"><b>AAAI17<b></td>
​      <td><b><a href="https://arxiv.org/pdf/1604.03635.pdf">RNN_LSTM</a><b></td>
​      <td><sub><b><i>19.0/17.1</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>      
   <tr>
​      <td rowspan="1"><b>ICIPI17<b></td>
​      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8296360">AP_RCNN</a><b></td>
​      <td><sub><b><i>38.5/-
​                     53.0/-(*)</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td rowspan="8"><b>Others<b></td>
​      <td><b><a href="https://arxiv.org/pdf/2006.02609.pdf">UnsupTrack</a><b></td>
​      <td>-</td>
​      <td><sub>62.4/58.5<sub></td>
​      <td><sub>61.7/58.1<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/abs/2010.12138.pdf">CSTrack</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>75.6/73.3（*）</i></b><sub></td>
​      <td><sub><b><i>74.9/72.6（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/2004.01888.pdf">FairMOT</a><b></td>
​      <td><sub><b><i>60.6/64.7（*）</i></b><sub></td>
​      <td><sub><b><i>74.9/72.8（*）</i></b><sub></td>
​      <td><sub><b><i>73.7/72.3（*）</i></b><sub></td>
​      <td><sub><b><i>61.8/67.3（*）</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1905.02292.pdf">FMA</a><b></td>
​      <td>-</td>
​      <td>-</td>
​      <td><sub>47.4/-<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1901.06129.pdf">SAC</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>49.2/56.5
​                     69.6/68.6(*)</i></b>
​                     71.2/73.1(*)<sub></td>
​      <td><sub><b><i>52.7/57.9</i></b>
​                     54.7/62.3<sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1808.01562.pdf">TAT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>49.0/-</i></b><sub></td>
​      <td><sub><b><i>51.5/-</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1703.07402.pdf">DeepSORT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>61.4/62.2(*)</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
   <tr>
​      <td><b><a href="https://arxiv.org/pdf/1602.00763.pdf">SORT</a><b></td>
​      <td>-</td>
​      <td><sub><b><i>59.8/53.8(*)</i></b><sub></td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
​      <td>-</td>
   </tr>
</table></font>

### Recent MOT Papers

**StrongSORT** Yunhao Du, Yang Song, Bo Yang, Yanyun Zhao. StrongSORT: Make DeepSORT Great Again[[paper]](https://arxiv.org/pdf/2202.13514.pdf)[[code]](https://github.com/xxxxx)<br>
      
      
## Datasets

### Surveillance Scenarios

[PETS2009](http://www.cvg.reading.ac.uk/PETS2009/a.html) : An old dataset.<br>
[MOT dataset](https://motchallenge.net/) : A dataset for multi-person detection and tracking, mostly used.<br>
[UA-DETRAC](http://detrac-db.rit.albany.edu/) : A dataset for multi-car detection and tracking. <br>
[AVSS2018 Challenge](https://iwt4s2018.wordpress.com/challenge/) : AVSS2018 Challenge based on UA-DETRAC is opened!<br>
[DukeMTMC](http://vision.cs.duke.edu/DukeMTMC/) : A dataset for multi-camera multi-person tracking. <br>
[PoseTrack](https://posetrack.net/): A dataset for multi-person pose tracking. <br>
[NVIDIA AI CITY Challenge](https://www.aicitychallenge.org/): Challenges including "Traffic Flow Analysis", "Anomaly Detection" and "Multi-sensor Vehicle Detection and Reidentification", you may find some insteresting codes on their [Github repos](https://github.com/NVIDIAAICITYCHALLENGE)<br>
[Vis Drone](http://www.aiskyeye.com/views/index): Tracking videos captured by drone-mounted cameras.<br>
[JTA Dataset](http://imagelab.ing.unimore.it/imagelab/page.asp?IdPage=25): A huge dataset for pedestrian pose estimation and tracking in urban scenarios created by exploiting the highly photorealistic video game Grand Theft Auto V developed by Rockstar North.<br>
[Path Track](http://people.ee.ethz.ch/~daid/pathtrack/) A new dataset with many scenes.<br>
[MOTS](https://www.vision.rwth-aachen.de/page/mots) MOTS: Multi-Object Tracking and Segmentation. In CVPR 2019<br>

### Driving Scenarios

[KITTI-Tracking](http://www.cvlibs.net/datasets/kitti/eval_tracking.php) : Multi-person or multi-car tracking dataset.<br>
[MOTS](https://www.vision.rwth-aachen.de/page/mots) Multi-Object Tracking and Segmentation. In CVPR 2019<br>
[Apollo-Tracking](http://apolloscape.auto/tracking.html) 3D Lidar multi-object tracking.<br> 
[Baidu Trajectory](http://apolloscape.auto/trajectory.html) Interesting dataset for trajectory prediction for Autonomous drive, wait to be opened.<br>

## Review Papers

Wenhan Luo, Junliang Xing, Anton Milan, Xiaoqin Zhang, Wei Liu, and Tae-Kyun Kim, "Multiple Object Tracking: A Literature Review" [[paper]](http://pdfs.semanticscholar.org/3dff/acda086689c1bcb01a8dad4557a4e92b8205.pdf)<br>
P Emami,PM Pardalos,L Elefteriadou,S Ranka "Machine Learning Methods for Solving Assignment Problems in Multi-Target Tracking" [[paper]](http://xueshu.baidu.com/s?wd=paperuri%3A%28dcfbdc0f8f79fe44d9166fd2481e37aa%29&filter=sc_long_sign&tn=SE_xueshusource_2kduw22v&sc_vurl=http%3A%2F%2Farxiv.org%2Fpdf%2F1802.06897&ie=utf-8&sc_us=15766836095004964816)<br>
A 101 slide, Globally-Optimal Greedy Algorithms for Tracking a Variable Number of Objects [[paper]](http://vision.stanford.edu/teaching/cs231b_spring1415/slides/greedy_fahim_albert.pdf)<br>
Francisco Luque Sánchez, Siham Tabik, Luigi Troiano, Roberto Tagliaferri, Francisco Herrera, "Deep Learning in Video Multi-Object Tracking: A Survey" [[paper]](https://arxiv.org/pdf/1907.12740.pdf)<br>

## Evaluation Metric

**CLEAR MOT** : Bernardin, K. & Stiefelhagen, R. "Evaluating Multiple Object Tracking Performance: The CLEAR MOT Metric" [[paper]](https://cvhci.anthropomatik.kit.edu/images/stories/msmmi/papers/eurasip2008.pdf)<br>
**IDF1** : Ristani, E., Solera, Cucchiara, R. & Tomasi, C. "Performance Measures and a Data Set for Multi-Target, Multi-Camera Tracking" [[paper]](https://users.cs.duke.edu/~ristani/bmtt2016/ristani2016MTMC.pdf)<br>
**TrackEval** : [[GitHub]](https://github.com/JonathonLuiten/TrackEval)<br>
**Evaluation Code**: [[Python]](https://github.com/cheind/py-motmetrics) [[Matlab]](https://bitbucket.org/amilan/motchallenge-devkit/src/default/ )<br> 

## Researcher

**Computer Vision Group at RWTH Aachen University** [[webpage and source code]](https://www.vision.rwth-aachen.de/publications/0000/)<br>
**Anton Milan** [[webpage and his source code]](http://www.milanton.de/)<br>
**Laura Leal-Taixé** [[webpage and her source code]](https://lealtaixe.github.io/publications/)<br>
**Dynamic Vision and Learning Group** [[webpage and their source code]](https://dvl.in.tum.de/research/mot/)<br>
**Longyin Wen** [[webpage and his source code]](http://www.cbsr.ia.ac.cn/users/lywen/)<br>
**UCF** [[webpage]](http://crcv.ucf.edu/projects/tracking)<br>


## Open Source

### Online

**Tracking-Objects-Points** Zhou, Xingyi and Koltun, Vladlen and Kr{\"a}henb{\"u}hl, Philipp. Tracking Objects as Points[[paper]](https://arxiv.org/pdf/2004.01177v1.pdf)[[code]](https://github.com/xingyizhou/CenterTrack)<br>
**Towards-Realtime-MOT** Zhongdao Wang, Liang Zheng, Yixuan Liu, Shengjin Wang. Towards Real-Time Multi-Object Tracking. [[paper]](https://arxiv.org/pdf/1909.12605v1.pdf) [[code]](https://github.com/Zhongdao/Towards-Realtime-MOT)<br>
**Track-no-bnw** Bergmann P, Meinhardt T, Lealtaixe L, et al. Tracking without bells and whistles[J]. (ICCV2020). [[paper]](https://arxiv.org/pdf/1903.05625.pdf)[[code]](https://github.com/phil-bergmann/tracking_wo_bnw)<br>
**DeepMot** Yihong Xu Yutong Ban Xavier Alameda-Pineda Radu Horaud, "DeepMOT:A Differentiable Framework for Training Multiple Object Trackers" [[paper]](https://arxiv.org/pdf/1906.06618.pdf)[[code]](https://gitlab.inria.fr/yixu/deepmot)<br>
**TrackR-CNN,MOTS** Paul Voigtlaender and Michael Krause, "MOTS: Multi-Object Tracking and Segmentation" In CVPR2019 [[paper]](https://www.vision.rwth-aachen.de/media/papers/mots-multi-object-tracking-and-segmentation/MOTS.pdf)[[code]](https://github.com/VisualComputingInstitute/TrackR-CNN/tree/master)<br>
**Tracktor** Philipp Bergmann, Tim Meinhardt, Laura Leal-Taixe "Tracking without bells and whistles" In Arxiv [[paper]](https://arxiv.org/pdf/1903.05625.pdf)[[code]](https://github.com/phil-bergmann/tracking_wo_bnw)<br>
**DMAN** Zhu, Ji and Yang, Hua and Liu, Nian and Kim, Minyoung and Zhang, Wenjun and Yang, Ming-Hsuan "Online Multi-Object Tracking with Dual Matching Attention Networks" [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ji_Zhu_Online_Multi-Object_Tracking_ECCV_2018_paper.pdf) [[code]](https://github.com/jizhu1023/DMAN_MOT) In ECCV2018<br>
**LSST** Weitao Feng, Zhihao Hu, Wei Wu, Junjie Yan, Wanli Ouyang "Multi-Object Tracking with Multiple Cues and Switcher-Aware Classification" [[paper]](https://arxiv.org/abs/1901.06129) SOA tracker on MOT ranking list. No code now.<br>
**SST** Sun. S., Akhtar, N., Song, H., Mian A., & Shah M. (2018). Deep Affinity Network for Multiple Object Tracking[[paper]](https://arxiv.org/abs/1810.11780)[[code]](https://github.com/shijieS/SST): Interesting work and expect the author to update their DPM tracking results on MOT17 benchmark.<br>
**MOTDT** Long Chen, Haizhou Ai "Real-time Multiple People Tracking with Deeply Learned Candidate Selection and Person Re-identification" in ICME 2018 [[code]](https://github.com/longcw/MOTDT)[[paper]](https://www.researchgate.net/publication/326224594_Real-time_Multiple_People_Tracking_with_Deeply_Learned_Candidate_Selection_and_Person_Re-identification)!<br>
**TMPORT** : E. Ristani and C. Tomasi. Tracking Multiple People Online and in Real Time. in ACCV 2014 [[paper]](https://users.cs.duke.edu/~tomasi/papers/ristani/ristaniAccv14.pdf) [[code]](http://vision.cs.duke.edu/DukeMTMC/)<br>
**MOT-RNN** : Anton Milan, Seyed Hamid Rezatofighi, Anthony Dick, Konrad Schindler, Ian Reid "Online Multi-target Tracking using Recurrent Neural Networks"[[paper]](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking.pdf) [[code]](https://bitbucket.org/amilan/rnntracking) In AAAI 2017.<br>
**DeepSort** : Wojke, Nicolai and Bewley, Alex and Paulus, Dietrich "Simple Online and Realtime Tracking with a Deep Association Metric" [[paper]](https://arxiv.org/abs/1703.07402) [[code]](https://github.com/nwojke/deep_sort) In ICIP 2017<br>
**Sort** : Bewley, Alex and Ge, Zongyuan and Ott, Lionel and Ramos, Fabio and Upcroft, Ben "Simple Online and Realtime Tracking"[[paper]](https://arxiv.org/abs/1602.00763) [[code]](https://github.com/abewley/sort) In ICIP 2016.<br>
**MDP** : Yu Xiang, Alexandre Alahi, and Silvio Savarese "Learning to Track: Online Multi-Object Tracking by Decision Making
" [[paper]](http://openaccess.thecvf.com/content_iccv_2015/papers/Xiang_Learning_to_Track_ICCV_2015_paper.pdf) [[code]](http://cvgl.stanford.edu/projects/MDP_tracking/) In International Conference on Computer Vision (ICCV), 2015 <br>
**CMOT** : S. H. Bae and K. Yoon. "Robust online multi-object tracking based on tracklet confidence and online discriminative appearance learning" [[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Bae_Robust_Online_Multi-Object_2014_CVPR_paper.pdf) [[code]](https://cvl.gist.ac.kr/project/cmot.html) In CVPR 2014<br> 
**RCMSS** : Mohamed A. Naiel1, M. Omair Ahmad, M.N.S. Swamy, Jongwoo Lim, and Ming-Hsuan Yang "Online Multi-Object Tracking Via 
Robust Collaborative Model and Sample Selection"[[paper]](https://users.encs.concordia.ca/~rcmss/include/Papers/CVIU2016.pdf) [[code]](https://users.encs.concordia.ca/~rcmss/) Computer Vision and Image Understanding 2016 <br>
**MHT-DAM** : Chanho Kim, Fuxin Li, Arridhana Ciptadi, James M. Rehg "Multiple Hypothesis Tracking Revisited"[[paper]](https://www.cc.gatech.edu/~ckim314/papers/MHTR_ICCV2015.pdf) [[code]](http://rehg.org/mht/) In ICCV 2015<br>
**OMPTTH** : Jianming Zhang, Liliana Lo Presti and Stan Sclaroff, "Online Multi-Person Tracking by Tracker Hierarchy," [[paper]]() [[code]](http://cs-people.bu.edu/jmzhang/tracker_hierarchy/Tracker_Hierarchy.htm) Proc. Int. Conf. on Advanced Video and Signal Based Surveillance (AVSS), 2012.<br>
**SMOT** : C. Dicle, O. Camps, M. Sznaier. "The Way They Move: Tracking Targets with Similar Appearance" [[paper]](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Dicle_The_Way_They_2013_ICCV_paper.pdf) [[code]](https://bitbucket.org/cdicle/smot) In ICCV, 2013.<br>

### Batch

**muSSP** Wang C, Wang Y, Wang Y, et al. muSSP: Efficient Min-cost Flow Algorithm for Multi-object Tracking[C]. neural information processing systems, 2019: 423-432. [[paper]](http://papers.nips.cc/paper/8334-mussp-efficient-min-cost-flow-algorithm-for-multi-object-tracking)[[code]](https://github.com/yu-lab-vt/muSSP)<br>
**TNT** Gaoang Wang, Yizhou Wang, Haotian Zhang, Renshu Gu, Jenq-Neng Hwang "Exploit the Connectivity: Multi-Object Tracking with TrackletNet" [[paper]](https://arxiv.org/pdf/1811.07258.pdf) [[code]](https://github.com/GaoangW/TNT)<br>
**NT** Longyin Wen*, Dawei Du*, Shengkun Li, Xiao Bian, Siwei Lyu Learning Non-Uniform Hypergraph for Multi-Object Tracking, In AAAI 2019 [[paper]](http://www.cs.albany.edu/~lsw/papers/aaai19a.pdf)[[code]](https://github.com/longyin880815) Waited!<br>
**headTracking**: Shun Zhang, Jinjun Wang, Zelun Wang, Yihong Gong,Yuehu Liu: "Multi-Target Tracking by Learning Local-to-Global Trajectory Models" in PR 2015 [[paper]](https://www.researchgate.net/publication/265295656_Multi-Target_Tracking_by_Learning_Local-to-Global_Trajectory_Models) [[code]](https://github.com/gengshan-y/headTracking) seems like a repo.<br>
**IOU** : E. Bochinski, V. Eiselein, T. Sikora. "High-Speed Tracking-by-Detection Without Using Image Information" [[paper]](http://elvera.nue.tu-berlin.de/files/1517Bochinski2017.pdf) [[code]](https://github.com/bochinski/iou-tracker/) In International Workshop on Traffic and Street Surveillance for Safety and Security at IEEE AVSS 2017, 2017. <br>
**NMGC-MOT** Andrii Maksai, Xinchao Wang, Franc¸ois Fleuret, and Pascal Fua "Non-Markovian Globally Consistent Multi-Object Tracking
" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Maksai_Non-Markovian_Globally_Consistent_ICCV_2017_paper.pdf)[[code]](https://github.com/maksay/ptrack_cpp) In ICCV 2017<br>
**D2T** Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman, "Detect to Track and Track to Detect" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Feichtenhofer_Detect_to_Track_ICCV_2017_paper.pdf) [[code]](https://github.com/feichtenhofer/Detect-Track) In ICCV 2017<br>
**H2T** : Longyin Wen, Wenbo Li, Junjie Yan, Zhen Lei, Dong Yi, Stan Z. Li. "Multiple Target Tracking Based on Undirected Hierarchical Relation Hypergraph," [[paper]](http://www.cbsr.ia.ac.cn/users/lywen/papers/CVPR2014_HyperGraphMultiTargetsTracker.pdf) [[code]](http://www.cbsr.ia.ac.cn/users/lywen/) IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2014.<br>
**LDCT** : F. Solera, S. Calderara, R. Cucchiara "Learning to Divide and Conquer for Online Multi-Target Tracking" [[paper]](http://ieeexplore.ieee.org/document/7410854/) [[code page 1]](https://github.com/francescosolera/LDCT) [[code page 2]](http://imagelab.ing.unimore.it/imagelab/researchActivity.asp?idActivity=09) In Proceedings of International Converence on Computer Vision (ICCV), Santiago Cile, Dec 12-18, 2015<br>
**CEM** : Anton Milan, Stefan Roth, Konrad Schindler "Continuous Energy Minimization for Multi-Target Tracking" [[paper]](http://www.milanton.de/files/pami2014/pami2014-anton.pdf) [[code]](http://www.milanton.de/contracking/) in pami 2014<br>
**OPCNF** : Chari, Visesh and Lacoste-Julien, Simon and Laptev, Ivan and Sivic, Josef "On Pairwise Costs for Network Flow Multi-Object Tracking" [[paper]](https://arxiv.org/abs/1408.3304) [[code]](http://www.di.ens.fr/willow/research/flowtrack/) In CVPR 2015<br>
**KSP** : J. Berclaz, F. Fleuret, E. Türetken and P. Fua "Multiple Object Tracking using K-Shortest Paths Optimization" [[paper]](https://cvlab.epfl.ch/files/content/sites/cvlab2/files/publications/publications/2011/BerclazFTF11.pdf) [[code]](https://cvlab.epfl.ch/software/ksp)  IEEE Transactions on Pattern Analysis and Machine Intelligence, 2011.<br>
**GMCP** : Amir Roshan Zamir, Afshin Dehghan, and Mubarak Shah "GMCP-Tracker: Global Multi-object Tracking Using Generalized Minimum Clique Graphs" [[paper]](http://crcv.ucf.edu/papers/eccv2012/GMCP-Tracker_ECCV12.pdf) [[code]](http://crcv.ucf.edu/projects/GMCP-Tracker/) European Conference on Computer Vision (ECCV), 2012.<br>

### Driving Scenarios

**MOTBeyondPixels** Sarthak Sharma*, Junaid Ahmed Ansari*, J. Krishna Murthy, and K. Madhava Krishna Beyond Pixels: Leveraging Geometry and Shape Cues for Online Multi-Object Tracking In ICRA 2018 [[paper]](https://arxiv.org/abs/1802.09298)[[code]](https://github.com/JunaidCS032/MOTBeyondPixels)<br>
**CIWT** Aljoˇsa Oˇsep, Alexander Hermans Combined Image and World-Space Tracking in Traffic Scenes In ICRA 2017 [[paper]](https://www.vision.rwth-aachen.de/media/papers/paper_final_compressed.pdf) [[code]](https://github.com/aljosaosep/ciwt)<br>

### MCMT

**DeepCC** Ristani and C. Tomasi "Features for Multi-Target Multi-Camera Tracking and Re-Identification" In CVPR 2018 [[paper]](https://arxiv.org/pdf/1803.10859.pdf) [[code]](https://github.com/ergysr/DeepCC)<br>
**towards-reid-tracking** Lucas Beyer∗  Stefan Breuers∗ "Towards a Principled Integration of Multi-Camera Re-Identification andTracking through Optimal Bayes Filters"[[paper]](https://arxiv.org/pdf/1705.04608.pdf)[[code]](https://github.com/VisualComputingInstitute/towards-reid-tracking)<br>

### RGBD Tracking

**DetTA** Stefan Breuers, Lucas Beyer "Detection-Tracking for Efficient Person Analysis: The DetTA Pipeline" [[paper]](https://arxiv.org/abs/1804.10134)[[code]](https://github.com/sbreuers/detta)<br>

## Private Detection

**POI** : F. Yu, W. Li, Q. Li, Y. Liu, X. Shi, J. Yan. "POI: Multiple Object Tracking with High Performance Detection and Appearance Feature" [[paper]](https://arxiv.org/pdf/1610.06136.pdf) [[detection]](https://drive.google.com/open?id=0B5ACiy41McAHMjczS2p0dFg3emM) In BMTT, SenseTime Group Limited, 2016<br>

## New papers

### CVPR

#### 2017

Eldar Insafutdinov, Mykhaylo Andriluka, Leonid Pishchulin, Siyu Tang, Evgeny Levinkov, Bjoern Andres, Bernt Schiele "Art Track: Articulated Multi-Person Tracking in the Wild" [[paper]](https://arxiv.org/abs/1612.01465)<br>
Manmohan Chandraker, Paul Vernaza, Wongun Choi, Samuel Schulter "Deep Network Flow for Multi-Object Tracking" [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Schulter_Deep_Network_Flow_CVPR_2017_paper.pdf)<br>
Jeany Son, Mooyeol Baek, Minsu Cho, and Bohyung Han, "Multi-Object Tracking with Quadruplet Convolutional Neural Networks" [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Son_Multi-Object_Tracking_With_CVPR_2017_paper.pdf)<br>

#### 2018

Girdhar R, Gkioxari G, Torresani L, et al. Detect-and-Track: Efficient Pose Estimation in Videos[C].(CVPR2018)[[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Girdhar_Detect-and-Track_Efficient_Pose_CVPR_2018_paper.pdf)[[code]](https://rohitgirdhar.github.io/DetectAndTrack/)  
Rolling Shutter and Radial Distortion Are Features for High Frame Rate Multi-Camera Tracking[[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bapat_Rolling_Shutter_and_CVPR_2018_paper.pdf)   
Features for Multi-Target Multi-Camera Tracking and Re-Identification [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Ristani_Features_for_Multi-Target_CVPR_2018_paper.pdf)  

#### 2019

Self-Supervised Adaptation of High-Fidelity Face Models for Monocular Performance Tracking [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Raaj_Efficient_Online_Multi-Person_2D_Pose_Tracking_With_Recurrent_Spatio-Temporal_Affinity_CVPR_2019_paper.pdf)  
Eliminating Exposure Bias and Metric Mismatch in Multiple Object Tracking [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Maksai_Eliminating_Exposure_Bias_and_Metric_Mismatch_in_Multiple_Object_Tracking_CVPR_2019_paper.pdf)

### ICCV

A. Sadeghian, A. Alahi, S. Savarese, Tracking The Untrackable: Learning To Track Multiple Cues with Long-Term Dependencies [[paper]](https://arxiv.org/abs/1701.01909)<br>
Andrii Maksai, Xinchao Wang, Franc¸ois Fleuret, and Pascal Fua "Non-Markovian Globally Consistent Multi-Object Tracking
" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Maksai_Non-Markovian_Globally_Consistent_ICCV_2017_paper.pdf)[[code]](https://github.com/maksay/ptrack_cpp)<br>
Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman, "Detect to Track and Track to Detect" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Feichtenhofer_Detect_to_Track_ICCV_2017_paper.pdf) [[code]](https://github.com/feichtenhofer/Detect-Track)<br>
Qi Chu, Wanli Ouyang,  Xiaogang Wang, Bin Liu, Nenghai Yu "Online Multi-Object Tracking Using CNN-Based Single Object Tracker With Spatial-Temporal Attention Mechanism" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chu_Online_Multi-Object_Tracking_ICCV_2017_paper.pdf)<br>
**Track-no-bnw** Bergmann P, Meinhardt T, Lealtaixe L, et al. Tracking without bells and whistles[J]. (ICCV2020). [[paper]](https://arxiv.org/pdf/1903.05625.pdf)[[code]](https://github.com/phil-bergmann/tracking_wo_bnw)

### ECCV2018

Ren, Liangliang and Lu, Jiwen and Wang, Zifeng and Tian, Qi and Zhou, Jie "Collaborative Deep Reinforcement Learning for Multi-Object Tracking" [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Collaborative_Deep_Reinforcement_ECCV_2018_paper.pdf)<br>
Kim, Chanho and Li, Fuxin and Rehg, James M "Multi-object Tracking with Neural Gating Using Bilinear LSTM" [[paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Chanho_Kim_Multi-object_Tracking_with_ECCV_2018_paper.pdf)<br>

### New paper

M Fabbri, F Lanzi, S Calderara, A Palazzi "Learning to Detect and Track Visible and Occluded Body Joints in a Virtual World" [[paper]](https://www.researchgate.net/publication/323957071_Learning_to_Detect_and_Track_Visible_and_Occluded_Body_Joints_in_a_Virtual_World) [[code]] Waited!<br>
Cong Ma, Changshui Yang, Fan Yang, Yueqing Zhuang, Ziwei Zhang, Huizhu Jia, Xiaodong Xie "Trajectory Factory: Tracklet Cleaving and Re-connection by Deep Siamese Bi-GRU for Multiple Object Tracking" In ICME 2018 [[paper]](https://arxiv.org/abs/1804.04555)<br>
Kuan Fang, Yu Xiang, Xiaocheng Li and Silvio Savarese "Recurrent Autoregressive Networks for Online Multi-Object Tracking" In IEEE Winter Conference on Applications of Computer Vision (WACV), 2018. [[webpage]](http://yuxng.github.io/)<br>
Tharindu Fernando, Simon Denman, Sridha Sridharan, Clinton Fookes "Tracking by Prediction: A Deep Generative Model for Mutli-Person localisation and Tracking" In WACV 2018 [[paper]](https://arxiv.org/pdf/1803.03347.pdf)<br>

### Multi-person Face Tracking

Shun Zhang, Yihong Gong, Jia-Bin Huang, Jongwoo Lim, Jinjun Wang, Narendra Ahuja and Ming-Hsuan Yang "Tracking Persons-of-Interest via Adaptive Discriminative Features" In ECCV 2016 [[paper]](https://link.springer.com/content/pdf/10.1007%2F978-3-319-46454-1_26.pdf) [[code]](https://github.com/shunzhang876/AdaptiveFeatureLearning)<br>
Chung-Ching Lin, Ying Hung"A Prior-Less Method for Multi-Face Tracking in Unconstrained Videos" In CVPR 2018 [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lin_A_Prior-Less_Method_CVPR_2018_paper.pdf)<br>

### Multi-person Pose Tracking

Yuliang Xiu, Jiefeng Li, Haoyu Wang, Yinghong Fang, Cewu Lu "Pose Flow: Efficient Online Pose Tracking" [[paper]](https://arxiv.org/abs/1802.00977) Idea is interesting but the true source code is not opened.<br>
Bin Xiao, Haiping Wu, and Yichen Wei "Simple Baselines for Human Pose Estimation and Tracking" [[paper]](https://arxiv.org/pdf/1804.06208.pdf)[[code]](https://github.com/Microsoft/human-pose-estimation.pytorch)  
Girdhar R, Gkioxari G, Torresani L, et al. Detect-and-Track: Efficient Pose Estimation in Videos[C].(CVPR2018)[[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Girdhar_Detect-and-Track_Efficient_Pose_CVPR_2018_paper.pdf)[[code]](https://rohitgirdhar.github.io/DetectAndTrack/)
Multi-Person Articulated Tracking With Spatial and Temporal Embeddings [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jin_Multi-Person_Articulated_Tracking_With_Spatial_and_Temporal_Embeddings_CVPR_2019_paper.pdf)  

### Multi-camera Tracking

Rolling Shutter and Radial Distortion Are Features for High Frame Rate Multi-Camera Tracking[[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Bapat_Rolling_Shutter_and_CVPR_2018_paper.pdf)
CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification[[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_CityFlow_A_City-Scale_Benchmark_for_Multi-Target_Multi-Camera_Vehicle_Tracking_and_CVPR_2019_paper.pdf)]
