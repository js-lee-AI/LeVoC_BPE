# LeVoC_BPE

Length-aware Subword Vocabulary Construction (LeVoC) is an effective and easy-to-follow approach to machine translation that addresses the issue of over-segmentation in Byte Pair Encoding (BPE), particularly for morphologically rich languages like Korean. Over-segmentation can erode word semantics and lead to semantic confusion during training, ultimately degrading the overall translation quality.

LeVoC strategically incorporates longer words into the vocabulary. By utilizing an external monolingual Korean corpus, LeVoC extracts and integrates long words, effectively preserving morphological information and reducing semantic confusion.

Our experiments demonstrate that LeVoC not only significantly outperforms BPE, but also can be applied to and surpass current state-of-the-art morpheme-aware subword tokenization methods. We provide evidence that the difficulty in translating sentences with long words in Korean is associated with morphological compositionality, and LeVoC's ability to reduce semantic confusion during training leads to improved translation quality.

The code for LeVoC_BPE will be made publicly available in August. Stay tuned for updates.
