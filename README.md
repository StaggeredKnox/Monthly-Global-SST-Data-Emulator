# In Brief

• GISS-Earth data used, GCM of CMIP6 project was utilized to generate the dataset.

• VQ-VAE trained separately for reconstruction task using standard objective function.

• Scaled-Convolutional LSTM network leveraged for temporal modeling of latent tensors corresponding to SST maps.

• Generation of Spatio-temporal data happens while using both trained architectures, simultaneously. See figures for more clarity.

• Deepayan Chakraborty, Raj Kishore, Rupapriya Naskar, et al. A Comparative Study Of Generative Models as Surrogates of Earth System Models to Simulate Global Sea Surface Temperature. ESS Open Archive . July 31, 2025. [DOI: 10.22541/essoar.175396162.29110800/v1](https://essopenarchive.org/users/919323/articles/1320692-a-comparative-study-of-generative-models-as-surrogates-of-earth-system-models-to-simulate-global-sea-surface-temperature?commit=e3f374767b4043b7be9b035cf3caaa9ac823a40f). Manuscript submitted to ACM Transactions for Spatial Algorithms and Systems journal for peer-review.

# Figures

<!-- First row: Two side-by-side figures -->
<table>
  <tr>
    <td align="center">
      <img src="extras/vq-vae.png" width="500"/><br/>
      <strong>Figure 1: Reconstruction Task (VQ-VAE)</strong>
    </td>
    <td align="center">
      <img src="extras/convlstm.png" width="500"/><br/>
      <strong>Figure 2: Temporal Modeling (Scaled-ConvLSTM)</strong>
    </td>
  </tr>
</table>

<!-- Second row: One centered figure -->
<p align="center">
  <img src="extras/Generation.png" width="1000"/><br/>
  <strong>Figure 3: Generation of Data</strong>
</p>
