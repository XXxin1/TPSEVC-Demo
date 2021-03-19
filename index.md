## This is a demo webpage for paper Two-Pathway Style Embedding for Arbitrary Voice Conversion
- - -
## Abstract
Arbitrary voice conversion, in words, zero-shot voice conversion has attracted more attention of researchers. Although disentangling the linguistic and style representations for acoustic features is an effective way to achieve zero-shot voice conversion, how to convert a natural speaker style is challenging because the diversities of speech and the difficulties of completely decoupling.  For this, in this paper, we propose a Two-Pathway Style Embedding Voice Conversion framework (TPSE-VC) for realistic and natural speech conversion by simultaneously embedding sentence-level and phoneme-level style information. A novel attention mechanism is proposed  to attend to implement implicit alignment for style timber and content phoneme, and then embedding a phoneme-level style representation. In addition,  we consider embedding all time steps of style audio into a fixed-length vector to get the sentence-level style representation. Moreover TPSE-VC dose not require any pre-trained models, and is only trained with non-parallel data. Experimental results demonstrate that our method outperforms  state-of-the-art results on zero-shot voice conversion.
- - -


### Note all the speakers of sampled utterances are unseen in training stage.

| **Transcription** | "They say that vital evidence was not heard in the court." |
| :--- | :--- |
| **Source** | <audio src="wavs/p249_169_p257_035/origin_source_p249_169.wav" controls preload></audio> |
| :--- | :--- |
| **Target** | <audio src="wavs/p249_169_p257_035/origin_target_p257_035.wav" controls preload></audio> |
| :--- | :--- |
| **Target (Vocoder)** | <audio src="wavs/p249_169_p257_035/vocoder_targetp257_035.wav" controls preload></audio> |
| :--- | :--- |
| **Ours** | <audio src="wavs/p249_169_p257_035/converted_proposed.wav" controls preload></audio> |
| :--- | :--- |
| **Chou et.al.** | <audio src="wavs/p249_169_p257_035/converted_adainvc.wav" controls preload></audio> |
| :--- | :--- |
| **AutoVC** | <audio src="wavs/p249_169_p257_035/converted_autovc.wav" controls preload></audio> |
| :--- | :--- |
| **VQVC+** | <audio src="wavs/p249_169_p257_035/converted_vqvc+.wav" controls preload></audio> |
| :--- | :--- |

- - -

| **Transcription** | "Domestic orders have also fallen since January." |
| :--- | :--- |
| **Source** | <audio src="wavs/p264_135_p336_018/origin_source_p264_135.wav" controls preload></audio> |
| :--- | :--- |
| **Target** | <audio src="wavs/p264_135_p336_018/origin_target_p336_018.wav" controls preload></audio> |
| :--- | :--- |
| **Target (Vocoder)** | <audio src="wavs/p264_135_p336_018/vocoder_targetp336_018.wav" controls preload></audio> |
| :--- | :--- |
| **Ours** | <audio src="wavs/p264_135_p336_018/converted_proposed.wav" controls preload></audio> |
| :--- | :--- |
| **Chou et.al.** | <audio src="wavs/p264_135_p336_018/converted_adainvc.wav" controls preload></audio> |
| :--- | :--- |
| **AutoVC** | <audio src="wavs/p264_135_p336_018/converted_autovc.wav" controls preload></audio> |
| :--- | :--- |
| **VQVC+** | <audio src="wavs/p264_135_p336_018/converted_vqvc+.wav" controls preload></audio> |
| :--- | :--- |

- - -

| **Transcription** | "The west coast line is not just for middle England." |
| :--- | :--- |
| **Source** | <audio src="wavs/p264_025_p271_194/origin_source_p264_025.wav" controls preload></audio> |
| :--- | :--- |
| **Target** | <audio src="wavs/p264_025_p271_194/origin_target_p271_194.wav" controls preload></audio> |
| :--- | :--- |
| **Target (Vocoder)** | <audio src="wavs/p264_025_p271_194/vocoder_targep271_194.wav" controls preload></audio> |
| :--- | :--- |
| **Ours** | <audio src="wavs/p264_025_p271_194/converted_proposed.wav" controls preload></audio> |
| :--- | :--- |
| **Chou et.al.** | <audio src="wavs/p264_025_p271_194/converted_adainvc.wav" controls preload></audio> |
| :--- | :--- |
| **AutoVC** | <audio src="wavs/p264_025_p271_194/converted_autovc.wav" controls preload></audio> |
| :--- | :--- |
| **VQVC+** | <audio src="wavs/p264_025_p271_194/converted_vqvc+.wav" controls preload></audio> |
| :--- | :--- |

- - -

| **Transcription** | "This matter has still to come before the European Parliament." |
| :--- | :--- |
| **Source** | <audio src="wavs/p239_043_p255_090/origin_source_p239_043.wav" controls preload></audio> |
| :--- | :--- |
| **Target** | <audio src="wavs/p239_043_p255_090/origin_target_p255_090.wav" controls preload></audio> |
| :--- | :--- |
| **Target (Vocoder)** | <audio src="wavs/p239_043_p255_090/vocoder_targep255_090.wav" controls preload></audio> |
| :--- | :--- |
| **Ours** | <audio src="wavs/p239_043_p255_090/converted_proposed.wav" controls preload></audio> |
| :--- | :--- |
| **Chou et.al.** | <audio src="wavs/p239_043_p255_090/converted_adainvc.wav" controls preload></audio> |
| :--- | :--- |
| **AutoVC** | <audio src="wavs/p239_043_p255_090/converted_autovc.wav" controls preload></audio> |
| :--- | :--- |
| **VQVC+** | <audio src="wavs/p239_043_p255_090/converted_vqvc+.wav" controls preload></audio> |
| :--- | :--- |
