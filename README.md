# HumanProteinAtlasImageClassification

##The Idea of this Kernel

In this kernel I largely merged the fastai v1 starter by Horton and the fastai-RGBY by iafoss. I (in my opinion) simplified some stuffabout the dataset and loading. I added:

    Iterative Stratified splitting the dataset into train and validation
    Class weighted Focalloss (the alpha parameter)
    Oversampling of the dataset
    The now standart onecycle instead of multicycle learning

So far TTA also is less performant than the regular predict which I find confusing. So far I got into the top 20% with this which is nice.
Unfortunatley I dont't have time or ressources to train this as long as it should run. I also can't include the external dataset so the tops ranks are not reachable for me.
