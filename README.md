# OCR-free Document Understanding Transformers
The job of interpreting documents (e.g., invoices) is highly important, but it may be challenging since it requires performing complex tasks such as reading text and having a total understanding of the document. Present Visual Document Understanding (VDU) methods rely on deep learning-based Optical Character Recognition (OCR) engines (e.g., Tesseract) for reading the text, and a post-processing function uses the OCR output to comprehend the document (e.g., BERT), the results obtained from the current VDU methods using OCR are exceptional, but OCR dependent methods are computationally expensive and are inflexible with different languages and can easily generate errors for the subsequent post-processing function. To address this issue an OCR-free Visual Document Understanding model is proposed which uses transformers architecture with a certain pretraining objective that makes the entire system learn more about document structure and inherent properties that every document comes with and then passes it through the Transformer decoder that uses Pre-train 'Bart-model' to which the first sequence that we give is the prompt that kind of hints the decoder to what kind of thing to decode.
=================================================================================================================================================================================
Developed an OCR-free VDU model overcoming OCR limitations in cost, flexibility, and error propagation.
• Proposed a simple Transformer-based design as the first step in OCR-free VDU research.
• Extensively tested the model for speed and accuracy validation.
• The model showcased superior performance and cost-effectiveness on both internal and external datasets
