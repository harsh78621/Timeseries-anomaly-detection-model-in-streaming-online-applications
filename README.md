 • Processedandnormalized4032datapointsfroma14-dayperiodwithdatarecordedevery5minutes,equating
 to 288timesteps per day.
 • Built and trained a Keras Sequential autoencoder with Conv1D and Conv1DTranspose layers, optimizing with
 AdamandMSEloss.
 • Determined a reconstruction error threshold of 0.1233. Samples with a reconstruction loss exceeding this threshold were identified as anomalies.
 • Identified 394 anomaly sample based on the reconstruction error threshold.
