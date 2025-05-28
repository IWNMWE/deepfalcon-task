# Calorimeter Showers

## Dataset  
The dataset consists of 125x125 images with three channels:  
- **ECAL**  
- **HCAL**  
- **Tracks**  

Along with features 'm0'(mass), 'pt'(transverse momentum), 'y'(labels for quark and gluon jet)

##Overview  

### **Variational Autoencoder (VAE)**  
- Implemented a VAE to learn the representation of the quark/gluon event images.  
- Provided side-by-side comparisons of original and reconstructed images.  

### **Jets as Graphs**  
- Converted non-zero pixel data into point clouds.  
- Constructed graphs from the point clouds using appropriate node and edge representations.  
- Trained a GNN for classification of quark/gluon jets.  
- Evaluated and reported model performance.  

### **Graph Autoencoder (GAE)**  
- Implemented a simple Graph Autoencoder.  
- Compared reconstruction results to the VAE model using suitable evaluation metrics.  

## Results  
- Visual comparisons of original vs. reconstructed events are available.  
- Performance metrics and observations/inferences are documented in the corresponding task files.