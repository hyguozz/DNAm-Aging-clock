
# DNAm-Aging-clock
An epigenetic clock is composed of a set of CpG sites whose DNA methylation (DNAm) levels measure the age of the subject. Extensive research is aimed at the potential to quantify biological aging rates and test longevity or rejuvenating interventions. I developed two deep learning based DNAm pan-tissue clocks to predict the age of the subject using the DNAm profiles of multiple tissues: Federated learning based aging clock and Auxiliary learning based aging clock.
# Federated Learning (FL)
FL is a deep learning paradigm where several entities (clients) collaborate in training a shared global model with a central server from decentralized data scattered among many clients. Each client trains its local model on the local data and communicate weight updates back to the server for aggregation. FL is a promising approach for distributed machine learning in situations where data cannot be uploaded for protecting clients’ privacy. Therefore, FL is well suited for healthcare applications as it enables gaining insights collaboratively, e.g., in the form of a consensus model, without moving patient data beyond the firewalls of the institutions in which they reside. 
# The auxiliary learning based aging clock
The auxiliary learning based aging clock is constructed with two parts: the main task is the supervised regression task which trained targeting on the chronological age, and the auxiliary task is a self-supervised learning (SSL) model which utilizes the variational auto-encoder (VAE) to detect the important structure in the input patterns. 

Both DNAm aging clocks, FL-based and Auxiliary based aging clocks, have outperformed the existed aging clocks with higher age prediction accuracies. 
