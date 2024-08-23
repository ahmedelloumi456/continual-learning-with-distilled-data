# continual learning with distilled data
 innovation in continual learning

this project builds on the work in :https://github.com/VICO-UoE/DatasetCondensation
Cited as : 
@article{zhao2022synthesizing,
  title={Synthesizing Informative Training Samples with GAN},
  author={Zhao, Bo and Bilen, Hakan},
  journal={NeurIPS 2022 Workshop on Synthetic Data for Empowering ML Research},
  year={2022}
}


Please download the synthetic sets from (refer to the code) https://drive.google.com/drive/folders/1NEnf_85Hpa2fhztWIxsiDQC1C2w_1YQA
which are learned in the continual learning scenario and put them into the data path named "cl_data"

additionaly , the cifar10 and cifar100 real image datasets are downloaded through pytorch's API(dowload=True) in the folder "data"
