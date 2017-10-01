1. Clone nlp-research-box-rambo (https://github.com/terminal-labs/nlp-research-box-rambo) and follow the setup instructions there 
  This will produce the needed environment in a vm for this replication
2. Clone this repo at the root level of your vm (run git clone https://github.com/RBrynsvold/Capstone.git from /home/vagrant)
3. Execute the bash script that will run a wget command to pull the cleaned data from the mirror repo 
  bash /home/vagrant/Capstone/bash_scripts/wget_download_from_mirror.sh
4. Execute the dimensional reduction script
  python /home/vagrant/Capstone/bash_scripts/dim_reduction_corp_class.py
  **Rachel's self-reminder note - change script name for final**
5. Execute the lda fitting script
6. Inspect the results of your fitted model inside a jupyter notebook!
   **to be added: the jupyter tunneling instructons**