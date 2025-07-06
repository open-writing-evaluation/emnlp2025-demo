# Chinese GEC Applications for L2 Learning
This repository hosts links to the web and mobile applications introduced by the paper **Chinese GEC Applications Supporting L2 Writing from Translation-Based to Immersive Learning**. Submitted to *EMNLP 2025 System Demonstrations*.

## Web Application (*Write it Right!*)
### Requirements
The web application is designed to operate in any browser environment with essentials such as active scripting (JavaScript), HTTP requests, and CSS enabled. 

For the best experience, we recommend using the latest versions of browsers such as Chrome and Mozilla Firefox.

### Access Link
Please use the following hyperlink to access the [web application](http://47.80.13.29/).

### Usage Instructions
The following section will briefly introduce the application's UI and features.

1. Upon entering the website, users will be greeted by a text box where they can begin writing.
    - The web application supports grammar error corrections for Chinese text in paragraph form.
2. Users can press submit to obtain grammar error corrections. 
    - A loading spinner will appear the interim while the system completes its analysis. 
3. Once the processing is complete, the results will appear in a section below the input text box. 
    - The results section will present the corrections in the format of an annotated sentence, where deletions and insertions are highlighted in red and green, respectively.
    - Users could opt to press to "Hide Annotations" button, to display a clean version of the corrected sentence without the colored highlights. In addition, users can press the same button, now "Show Annotations", to view the annotated version again.
### Screen Captures
<table>
    <tr>
        <td align="center">Annotated Results</td>
        <td align="center">Corrected Results</td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/user-attachments/assets/f54ef6c4-d7cb-448b-bfda-82e0a31f2689" alt="web_app_anno" width = 100% height = 100%></td>
        <td align="center"><img src="https://github.com/user-attachments/assets/90af99b1-bf39-4678-af56-9455c82cfc40" alt="web_app_corr" width = 100% height = 100%></td>
    </tr> 
</table>

## Mobile Application (*Translate it Right!*)
### Requirements
The mobile application is built to run in Android environments. The application requires Android operating systems versioned Android 7.0 and above (SDK 24). The application was tested on Android 14 and 15 during development. For a smooth experience, a stable internet connection is recommended.

### Access Link
Please use the following hyperlink to download the [APK file](https://drive.google.com/file/d/1dPqAWHHMbSyDizz6p_kygUCQkK3hhK7Z/view?usp=sharing) (Google Drive Link).

APK files are installer files native to Android. To install our application, please follow these steps:
1. Download the APK file via the aforementioned link.
2. Navigate to the downloads folder on your Android device, then press on the downloaded APK file to install the application.
3. You will likely receive a system warning similar to "For your security, your phone is not allowed to install unknown apps from this source." with options to either cancel the installation or navigate to settings. Press settings, enable **Allow from this source**, then press back to return to the install process.
4. You can launch the application once the installation is complete.

In addition to Android devices, the application can also operate on Android emulators such as the official emulator in Google's Android Studio IDE.  
### Usage Instructions
The following section will briefly introduce the application's UI and features.
1. Language Selection
    - Users are prompted to first select an exercise language (i.e. the language they want to practice) and a feedback language (i.e. the language they are familiar with). 
    - The mobile application currently supports English -> Chinese and Chinese -> English translation exercises.
2. Translation Exercise
    - Users will be presented with a sentence sourced from a question bank in their chosen feedback language.
    - Users will try to translate the given sentence, and type their answer in the available text field.
    - Users could use the refresh button to switch to another exercise sentence.
3. Exercise Results
    - After pressing "Submit", users will be taken to the "Results" screen after the server backend completes its analysis. In the interim, users will be greeted by a loading screen. 
    - The "Results" screen contains three sections: (i) the input sentence (the user's answer), (ii) the annotated sentence, where deletions and insertions are highlighted in red and green, respectively, and (iii) LLM feedback to provide guidance based on the errors made in the user's answer. 
    - Users can choose to either start a new exercise or save the current exercise. 
4. Exercise History
    - Contains a list view of saved exercises.
    - Users can swipe left 
to bring up a modal view that includes the details of each saved entry or swipe right to delete the entry from exercise history.
    - Users could also utilize the "Clear History" button to delete all exercise history.
### Screen Captures

<table>
    <tr>
        <td align="center">Language Selection</td>
        <td align="center">Translation Exercise</td>
        <td align="center">Input Screen</td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/user-attachments/assets/cfc52bf2-8834-414c-81df-dae5a444a52a" alt="select_lang" width = 80% height = 80%></td>
        <td align="center"><img src="https://github.com/user-attachments/assets/28ecf70a-e96c-40fa-8c73-a17178678246" alt="question" width = 80% height = 80%></td>
        <td align="center"><img src="https://github.com/user-attachments/assets/c2f65778-624d-4397-b3a5-e46486ab5c7d" alt="input" width = 80% height = 80%></td>
    </tr>
    <tr>
        <td align="center">Exercise Results</td>
        <td align="center">Exercise History</td>
        <td align="center">History Modal</td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/user-attachments/assets/44787bbb-76ea-4cfb-a7a8-07201222d566" alt="output" width = 80% height = 80%></td>
        <td align="center"><img src="https://github.com/user-attachments/assets/96c25091-21af-40f6-8367-c996866fa3a6" alt="history_list" width = 80% height = 80%></td>
        <td align="center"><img src="https://github.com/user-attachments/assets/1be11492-bf71-41a5-b043-6734488cbfec" alt="history_modal" width = 80% height = 80%></td>
    </tr>
</table>


## Demo Video
Click the [link here](https://youtu.be/XvkQKiO0PaQ) for a demo video showcasing both applications (web and mobile).

