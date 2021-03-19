## This is a demo webpage for paper Two-Pathway Style Embedding for Arbitrary Voice Conversion
- - -
## Abstract
Arbitrary voice conversion, in words, zero-shot voice conversion has attracted more attention of researchers. Although disentangling the linguistic and style representations for acoustic features is an effective way to achieve zero-shot voice conversion, how to convert a natural speaker style is challenging because the diversities of speech and the difficulties of completely decoupling.  For this, in this paper, we propose a Two-Pathway Style Embedding Voice Conversion framework (TPSE-VC) for realistic and natural speech conversion by simultaneously embedding sentence-level and phoneme-level style information. A novel attention mechanism is proposed  to attend to implement implicit alignment for style timber and content phoneme, and then embedding a phoneme-level style representation. In addition,  we consider embedding all time steps of style audio into a fixed-length vector to get the sentence-level style representation. Moreover TPSE-VC dose not require any pre-trained models, and is only trained with non-parallel data. Experimental results demonstrate that our method outperforms  state-of-the-art results on zero-shot voice conversion.
- - -


### Note all the speakers of sampled utterances are unseen in training stage.
| **Transcription** | "They say that vital evidence was not heard in the court." |
| :--- | :--- |
| **Source** | <audio src="wavs/p249_169_p257_035/origin_source_p249_169.wav" controls preload></audio> |
| --- | --- |
| **Target** | <audio src="wavs/p249_169_p257_035/origin_target_p257_035.wav" controls preload></audio> |
| --- | --- |
| **Target (Vocoder)** | <audio src="wavs/p249_169_p257_035/vocoder_targetp257_035.wav" controls preload></audio> |
| --- | --- |
| **Ours** | <audio src="wavs/p249_169_p257_035/converted_proposed.wav" controls preload></audio> |
| --- | --- |
| **Chou et.al.** | <audio src="wavs/p249_169_p257_035/converted_adainvc.wav" controls preload></audio> |
| --- | --- |
| **AutoVC** | <audio src="wavs/p249_169_p257_035/converted_autovc.wav" controls preload></audio> |
| --- | --- |
| **VQVC+** | <audio src="wavs/p249_169_p257_035/converted_vqvc+.wav" controls preload></audio> |
| --- | --- |

| **Source** | **Target** | **Ours Converted** | **Chou** | **AutoVC** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="all/all/unseen/p330_p347_3/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_3/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_3/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_3/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_3/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p347_p330_2/source.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_2/target.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_2/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_2/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_2/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p330_p347_1/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_1/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_1/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_1/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_1/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p330_p361_1/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p361_1/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p361_1/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p361_1/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p361_1/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p347_p330_3/source.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_3/target.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_3/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_3/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_3/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
