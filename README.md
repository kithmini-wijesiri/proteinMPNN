# proteinMPNN

ProteinMPNN is a powerful tool designed to address the inverse problem of protein design: given a fixed protein backbone structure, it predicts the optimal amino acid sequence that fits this structure. Unlike AlphaFold and Rosettafold, which focus on predicting protein structures from sequences, ProteinMPNN is used to redesign protein sequences to match a specified backbone.

Packages for ProteinMPNN can be installed by running:

conda create --name pmpnn_tutorial

conda activate pmpnn_tutorial

conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch

pip3 install -r requirements.txt

Display the help information of the main ProteinMPNN application by running

python ~/rosetta_workshop/ProteinMPNN/protein_mpnn_run.py -h
