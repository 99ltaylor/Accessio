<p align="center">
<img src="https://media.giphy.com/media/IIWi4Qwtl5mM9JbMF4/giphy.gif" alt="animation1" />
</p>

<h2 align="center">Training Natural Language Processing AI (NLP) to support people with additional needs into education and/or into the workforce, no matter their spoken language or dialect.<br>
<br></h2>

<h3>Problem</h3>
In Jamaica, only 15% of the population living with disabilities are registered to receive their eligible benefits & support. Thousands of people, like my Aunty Angela, go unsupported. People face technical difficulties in the registration process. Speech recognition technology can help. However, current technology doesn’t understand Jamaican Patois because AI algorithms are not trained with relevant datasets.
 
<h3>Solution</h3>

Accessio will develop NLP datasets for Jamaican Patois. For the first time, people with disabilities, who speak Patois as their first language, will also be able to access assistive technologies using their native language.

Accessio is an open-source web app that can be used on smartphones or web browsers. See ‘Technology’ below for more details.
 
<h3>Landscape</h3>

In 2022, AI’s biggest names (DeepMind, open-ai, Hugging Face) will take steps to improve the use and development of Natural Language Processing technology.

However, current NLP tech is trained on traditional written sources such as newspapers, books, and articles which use standard, formal forms of language. A language is rarely spoken in exactly the same way by everyone, and different groups of people will have their own accent, dialect, slang, etc.

NLP is yet to be developed for Jamaican Patois and other Caribbean languages and dialects.

<h2>Technology</h2>

<h3>Input</h3>
* Accessio listens to the user.

<h3>Process</h3>
* The user's speech is converted to text.
* The text is converted to NLP tokens and processed through transformers specifically trained to understand Jamaican Patois.

<h3>Output</h3>
* Accessio provides an appropriate response.

<h2>7-Step Machine Learning Workflow</h2>

![Screenshot 2021-12-07 at 22 26 51](https://user-images.githubusercontent.com/61777002/145180303-22a92b9c-6d0d-4aee-a778-f0fcb40e6394.png)
<br>Source: [Google Cloud tutorial](https://cloud.google.com/ai-platform/docs/ml-solutions-overview?utm_source=youtube&utm_medium=unpaidsoc&utm_campaign=CDR_guo_aiml_nkw8ndu7mjw_010521&utm_content=description 
)

<details open>
<summary>Step 1: Source & prepare data</summary>
 <br>
<ul>Primary research: Facilitate and capture honest, open conversations about living with a full range of disabilities in Jamaica.</ul>
<ul>Secondary research: Collect relevant disabilities information to be used to train Accessio on facts, figures and process relasted to specific disabilities.</ul>
</details>

<details>
<summary>Step 2: Code your model</summary>
</details>

<details>
<summary>Step 3: Train, evaluate and tune your model</summary>
</details>

<details>
<summary>Step 4: Deploy your trained model</summary>
</details>

<details>
<summary>Step 5: Get predictions from your model</summary>
</details>

<details>
<summary>Step 6: Monitor the ongoing predictions</summary>
</details>

<details>
<summary>Step 7: Manage your models and versions</summary>
</details>



<h3 align="center">Input: Text from numerous sources</h3>
<p align="center"> <img src="https://user-images.githubusercontent.com/61777002/145097309-abc181da-0d06-4bf6-9a81-ba5697a7b591.png" alt="still_inputs" /> </p>
<p align="center"> <img width="100" src="https://user-images.githubusercontent.com/61777002/145086586-ca25b590-6565-4a28-9a64-27fa1c3ff354.png" alt="plain_arrow" /> </p>
<h3 align="center">Process: Natural Language Processing Technology</h3>
<p align="center">

 ![NLP Process Accessio](https://user-images.githubusercontent.com/61777002/145103951-4c10c050-a56c-4511-bd1f-aa6fba470f13.gif)

</p>
<p align="center"> <img width="100" src="https://user-images.githubusercontent.com/61777002/145086586-ca25b590-6565-4a28-9a64-27fa1c3ff354.png" alt="plain_arrow" /> </p>
<h3 align="center"> Example Output : Step-by-step process of applying for a young person's Education, Health and Care Plan (UK) </h3>
<p align="center"><img width="1100" alt="[EHC Plan Application Process]" src="https://user-images.githubusercontent.com/61777002/145069264-c4410ab9-953c-4dbe-b0f8-2e536fd741d7.png"> <em>Click image to expand</em></p>

---
<h1>Development</h1>
<h3>User Stories </h3>
<details open>
<summary>Basic</summary>

```
As a user,
I want to see a filtered list of relevant assistive technology funding opportunities, 
So I can narrow my applications to only the opportunities for which I am eligible.
```
```
As a user,
I want to compare funding opportunities in a table format,
So I can compare all relevant funding opportunities on one screen.
```
```
As a user,
I want to have a step-by-step list of the entire application process,
So I have no surprises or requests for random pieces of information or evidence.
```
</details>
<h4>Disability specific</h4>
<details>
<summary>Dyslexic User</summary> 
 
```
As a dyslexic user,
I want to have a step-by-step customer journey map of the entire application process,
So I canvisualise the whole process in one image.
```
</details>
<details>
<summary>Keyboard-Only User</summary>

```
As keyboard-only user,
I want to be able to reach the main navigation links with a keyboard,
so that I can determine the different areas of the site.
```
```
As keyboard-only user,
I want the ability to reach all links (text or image), form controls and page functions,
so that I can perform an action or navigate to the place I choose.
```
```
As a keyboard-only user,
I want the ability to use the enter key to open the selected link,
so that every link on a page is accessible using a keyboard as it would be with a left mouse click.
```
```
As keyboard-only user,
I want to know where I am on the screen at all times,
so that I know what I can do and how to do it.
```
</details>
<details>
<summary>Screen Reader User</summary>

```
As a screen reader user,
I want to hear the text equivalent for each image conveying information,
so that I don’t miss any information on the page.
```
```
As a screen reader user,
I want to hear the text equivalent for each image button,
so that I will know what function it performs.
```
```
As a screen reader user,
I want to understand know what each form label is for each form field,
so that I can effectively enter the correct information in the form.
```
```
As a screen reader user,
I want to know what the column and row headers for each table cell,
so that I can understand the meaning of the data.
```
</details>
<details>
<summary>User with Low-Vision</summary>

```
As a user who has trouble reading due to low vision,
I want to be able to make the text larger on the screen,
so that I can read it.
```
</details>
<details>
<summary>User with Color-blindness</summary>

```
As a user who is color blind,
I want to have access to information conveyed in color,
so that I do not miss anything and I understand the content.
```
```
As a user who is color blind,
I want to links to be distinguishable on the page,
so that I can find the links and navigate the site.
```
```
As a user who is color blind,
I want to know what fields are required,
so that I can fill out the form.
```
</details>
<details>
<summary>Hearing Impaired User</summary>

```
As a user who is hearing-impaired,
I want a transcript of the spoken audio,
so that I can have access to all information provided in audio clips.
```
```
As a user who is hearing-impaired,
I want to turn on video captions,
so that I can understand what is being said in videos.
```
</details>
<h3>Learning & Resources</h3>
<h4>Accessibility & Assistive Technology</h4>
<h4>AI, Machine Learning, & Natural Language Processing</h4>
<details>
<summary>LinkedIn Learning, udemy & Makers Academy</summary>
<ul>
  <li><a href="https://www.linkedin.com/learning/nlp-with-python-for-machine-learning-essential-training/what-you-should-know?autoAdvance=true&autoSkip=true&autoplay=true&resume=false">NLP with Python for Machine Learning Essential Training</a></li>
<li><a href="https://www.linkedin.com/learning/unit-testing-and-test-driven-development-in-python/welcome?autoAdvance=true&autoSkip=false&autoplay=true&resume=true">Unit Testing & Test Driven Development in Python</a></li>
<li><a href="https://www.linkedin.com/learning/azure-machine-learning-development-1-basic-concepts/what-you-should-know?autoAdvance=true&autoSkip=true&autoplay=true&resume=false">Azure Machine Learning Development: 1 Basic Concepts</a></li>
<li><a href="https://www.linkedin.com/learning/advanced-nlp-with-python-for-machine-learning/leveraging-the-power-of-messy-text-data?autoAdvance=true&autoSkip=false&autoplay=true&resume=true">Advanced NLP with Python for Machine Learning</a></li>
<li><a href="https://www.linkedin.com/learning/design-thinking-data-intelligence/welcome?autoAdvance=true&autoSkip=false&autoplay=true&resume=true">Design Thinking: Data Intelligence</a></li>
<li><a href="https://www.linkedin.com/learning/deep-learning-foundations-natural-language-processing-with-tensorflow/leveraging-deep-learning-for-natural-language-processing?autoAdvance=true&autoSkip=false&autoplay=true&resume=true">Deep Learning Foundations: Natural Language Processing with TensorFlow</a></li>
<li><a href="https://www.udemy.com/course/django-python-advanced/">Build a Backend REST API with Python & Django - Advanced</a></li>
<li><a href="https://makersstudents.slack.com/archives/CJ94H1P6U">Makers Algorithm course - #Algorithm channel on Slack</a></li>
</ul>
</details>
<details>
<summary>Books</summary>
<ul>
<li><a href="https://www.manning.com/books/grokking-algorithms">'Algorithms', by Grokking</a></li>
<li><a href="https://automatetheboringstuff.com/">'Automate the boring stuff with Python', by Sweigart</a></li>
</ul>
</details>
<details>
<summary>Videos and Podcasts</summary>
<ul>
<li><a href="https://www.avclub.com/black-mirror-be-right-back-1798178877">Netflix - Black Mirror: “Be Right Back”</a></li>
<li><a href="https://law.unimelb.edu.au/news/caide/black-mirrors-hated-in-the-nation-facial-recognition-is-a-weapon">Netflix - Black Mirror: “Hated in the Nation”</a></li>
<li><a href="https://www.bbc.co.uk/sounds/play/m001216j">BBC iPlayer, The Reith Lectures, Stuart Russell - Living With Artificial Intelligence</a></li>
<li><a href="https://deepmind.com/blog/article/welcome-to-the-deepmind-podcast">DeepMind</a></li>
</ul>
</details>
