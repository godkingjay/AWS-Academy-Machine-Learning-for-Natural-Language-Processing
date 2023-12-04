# Module 7 Knowledge Check

1. **What is syntax?**
    - [ ] Rules for extracting meaning from text
    - [x] The order and structure for words in sentences
    - [ ] A method for understanding context
    - [ ] Two words with the same meaning

2. **Which of the following is an example of syntax?**
    - [ ] Rules that determine how to spell words
    - [x] Noun and adjective order
    - [ ] Capitalization rules
    - [ ] Rules that define proper nouns

3. **What is morphology?**
    - [ ] A description of the way that verbs and nouns are combined in a language
    - [ ] A description of the structure of a language
    - [x] A description of how words are formed by adding prefixes and suffixes
    - [ ] Rules for how to create plurals

4. **Which statement is true about the relationship between statistical machine translation (SMT) and neural machine translation (NM T)?**
    - [ ] SMT is better at understanding context.
    - [ ] SMT is better at translating between languages with dramatic differences in word order.
    - [ ] NMT is better at translating longer sentences.
    - [x] NMT systems were developed after SMT systems.

5. **Which Amazon service can detect the language of a text?**
    - [ ] Amazon Polly
    - [ ] Amazon Transcribe
    - [ ] Amazon SageMaker
    - [x] Amazon Comprehend

6. **What is the purpose of a Speech Synthesis Markup Language (SSML) tag?**
    - [x] To change the way that Amazon Polly vocalizes words
    - [ ] To indicate the Start and end Of a sentence
    - [ ] To select which voice Amazon Polly should use
    - [ ] To select a Neural Text-to-Speech (NTTS) voice

7. **Which file formats does Amazon Transcribe support to export results?**
    - [ ] Plaintext
    - [ ] JSON and YAML
    - [x] JSON only
    - [ ] YAML only

8. **If the audio file for an Amazon Transcribe job contains multiple channels, a single JSON file is exported.**
    - [x] True
    - [ ] False

9. **What would the following Speech Synthesis Markup Language (SSML) tag accomplish?**

    `<break strength="Strong">`

    - [x] Cause Amazon Polly output to pause for a predefined length.
    - [ ] Nothing. Strength is not an option for break.
    - [ ] Cause Amazon Polly output to increase the audio volume.
    - [ ] Cause Amazon Polly output to repeat a word.

10. **What does the following code do?**

    ```python
    def transcribe_file(job_name, file_uri, transcribe_client):
        transcribe_client.start_transcription_job(
            TranscriptionJobName=job_name,
            Media={'MediaFileUri': file_uri},
            MediaFormat='wav',
            LanguageCode='en-US'
        )
    ```

    - [ ] Results in an error
    - [ ] Starts a transcription job
    - [x] Defines a transcription job that can be executed later
    - [ ] Creates a new instance of a transcribe client
