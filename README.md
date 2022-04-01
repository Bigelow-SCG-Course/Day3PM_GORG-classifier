## Assignment of Function and Taxonomy to Metagenomic Reads using the GORG-classifier

For this lesson, we are going to work with output data from the [GORG-classifier](https://github.com/BigelowLab/gorg-classifier).  The GORG-classifier uses Kaiju to compare metagenomic reads to high quality genomes from GORG-Tropics to provide functional and taxonomic annotations to each individual read.  If you want to install and run the GORG-classifier on your own, you can find installation instructions on its [github page](https://github.com/BigelowLab/gorg-classifier).

For the purpose of today's lesson, we've run the GORG-classifier for you on some pet metagenomes from BATS. See [GORG-classifier_setup.ipynb](https://github.com/Bigelow-SCG-Course/Day3PM_GORG-classifier/blob/main/GORG-classifier_setup.ipynb) for details.

## Setup your lesson environment

If you haven't already, let's create a directory for this lesson in your user lab.  

In terminal, navigate over to your user lab directory and clone the lesson repository.

```
$ cd ~/storage/user_lab/{your_username_here}/
$ git clone https://github.com/Bigelow-SCG-Course/Day3PM_GORG-classifier.git
```

You should now have a directory called '3PM_GORG-classifier' within your user directory.