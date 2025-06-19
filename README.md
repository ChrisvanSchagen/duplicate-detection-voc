# duplicate-detection-voc
This is a thesis project on duplicate and near-duplicate detection methods on historical VOC document transcriptions.

This notebook creates and evaluates three methods for duplicate detection on historical Dutch documents: TF-IDF, BiLSTM, and a Hybrid approach. The data used for this project can be found and downloaded here: GLOBALISE project, 2024, "VOC transcriptions v2 - GLOBALISE", https://hdl.handle.net/10622/LVXSBW, IISH Data Collection, V1.

Additionally, to locate the exact documents within those transcription archives, the csv file "NT00348_OBP" is used, which is included in this repository.

For the BiLSTM and Hybrid models, pre trained embeddings are used. The embeddings are pretrained using the Word2Vec model by GLOBALISE (van Wissen, Leon, and GLOBALISE. “GLOBALISE Word2vec Experiment”. Zenodo, March 17, 2025. https://doi.org/10.5281/zenodo.15038313.) The embedding matrix loaded here was trained with different parameter values as originally in their experiment. Such as the context window or the minimum amount of occurences of a word. The exact details about this are explained in the thesis.