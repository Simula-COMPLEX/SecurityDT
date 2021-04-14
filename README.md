# Digital Twin-based Anomaly Detection in Cyber-physical Systems
# Authors:Qinghua Xu<sup>1</sup>; Shaukat Ali<sup>1</sup>; Tao Yue1<sup>2</sup>
1. Simula Research Laboratory, Norway
2. Nanjing University of Aeronautics and Astronautics, China

# Conference: ICST 2021: International Conference on Software Testing, Verification and Validation
# Abstract
Cyber-Physical  Systems  (CPS)  are  susceptible  tovarious anomalies during their operations. Thus, it is importantto detect such anomalies. Detecting such anomalies is challengingsince  it  is  uncertain  when  and  where  anomalies  can  happen.To   this   end,   we   present   a   novel   approach   called   AnomalydeTection with digiTAl twIN (ATTAIN), which continuously andautomatically builds a digital twin with live data obtained from aCPS for anomaly detection. ATTAIN builds a Timed AutomatonMachine  (TAM)  as  the  digital  representation  of  the  CPS,  andimplements  a  Generative  Adversarial  Network  (GAN)  to  detectanomalies. GAN uses a GCN-LSTM-based module as a generator,which  can  capture  temporal  and  spatial  characteristics  of  theinput  data  and  learn  to  produce  realistic  unlabeled  adversarialsamples.  TAM  labels  these  adversarial  samples,  which  are  thenfed  into  a  discriminator  along  with  real  labeled  samples.  Aftertraining, the discriminator is capable of distinguishing anomalousdata  from  normal  data  with  a  high  F1  score.  To  evaluate  ourapproach,  we  used  three  publicly  available  datasets  collectedfrom  three  CPS  testbeds.  Evaluation  results  show  that  ATTAINimproved the performance of two state-of-art anomaly detectionmethods by 2.413%, 8.487%, and 5.438% on average on the threedatasets,  respectively.  Moreover,  ATTAIN  achieved  on  average8.39%  increase  in  the  anomaly  detection  capability  with  digitaltwins as compared with an approach of not using digital twins

# Replication Package
[Download](https://github.com/Simula-COMPLEX/SecurityDT)

# Notes
Please note that the datasets used in this paper are provided by [iTrust](https://itrust.sutd.edu.sg/).
