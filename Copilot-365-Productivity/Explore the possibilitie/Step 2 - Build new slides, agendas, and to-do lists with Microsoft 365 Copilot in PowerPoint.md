# Build new slides, agendas, and to-do lists with Microsoft 365 Copilot in PowerPoint

Microsoft 365 Copilot in PowerPoint is an AI-powered feature that can help you create, design, and format your slides. You can type in what you intend to convey with your presentation, and Copilot helps you get it done.

Copilot can help you move past that initial blank slide and get you moving in the right direction. To start using Copilot in PowerPoint, you can open the **Copilot** pane via the Copilot icon in the ribbon's **Home** tab.

![Screenshot of the Copilot icon in the PowerPoint ribbon.](https://learn.microsoft.com/en-us/training/wwl/create-draft-content-with-microsoft-copilot-microsoft-365/media/copilot-ribbon-powerpoint.png)

From the Copilot pane, you can begin creating a new presentation from a Word document or about a desired topic. In the example, we start with a basic request to create a presentation about a topic and add other elements to make the prompt more robust.

![Screenshot of the Copilot panel in PowerPoint upon first opening.](https://learn.microsoft.com/en-us/training/wwl/create-draft-content-with-microsoft-copilot-microsoft-365/media/copilot-pane-powerpoint.png)

> Tip
>
> Currently, Copilot in PowerPoint is only able to create presentations from Word documents.


## Let's get crafting

If you haven't done so yet, download the following files and save the file to your **OneDrive folder** so they appear in your MRU list:

*   **_[Market Trend Report- Protein shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)_**

Note

Starting prompt:

```Create a new PowerPoint presentation.```

In this simple prompt, you start with the basic **Goal**: _to build a new PowerPoint presentation._ However, there's no information about what the presentation is about or what it should look like.

### Prompt guidance

Here’s how to structure prompts so Copilot understands what you want it to create:

| Element | Example |
|---------|---------|
| **Basic prompt** Start with a Goal: | "Create a new PowerPoint presentation about LLMs." |
| **Good prompt** Add Context: | "We need to present the advantages and the capabilities of using LLMs to students." |
| **Better prompt** Specify Source(s): | "…using the latest from /LLMsArchitecturesApplicationsandFutureInnovationsinArtificialIntelligence.docx." |
| **Best prompt** Set clear Expectations: |  "Please include an overview of the architecture, its key features and benefits and a comparison between some LLMs models in the market. Please use simple language." |


> Note
>
> **Crafted prompt**:
> 
> _Create a new PowerPoint presentation using the latest from **/LLMsArchitecturesApplicationsandFutureInnovationsinArtificialIntelligence.docx**. We need to present the advantages, capabilities, features and benefits to students. Please include an overview of the LLMs, their key features and benefits, and a comparison between some similar LLMs models in the market. Please use simple language._

With the **Goal**, **Context**, **Source**, and **Expectations** all laid out, Copilot has everything it needs to give you a great response.

### Referencing sources

As in the example, if you want Copilot to base your new presentation off a file you already have, you can tell it to do that. In the prompt window, select **Create presentation from file** to choose **_up to 3 files_** that Copilot should look at when creating your new document.

In the compose box, you can also enter "/" and the name of the file you'd like to reference, which will update the file options shown in the menu for selection.

Prompts:
Hebrew:
```
בהתבסס על המסמך האקדמי שנוצר בשלב הקודם, צור מצגת הדרכה לכיתה.

המצגת צריכה להיות בנויה באופן פדגוגי וברור, מחולקת לשקפים לפי הפרקים המרכזיים במסמך, ולכלול כותרת לכל שקף, נקודות עיקריות בתמציתיות (Bullets), דוגמאות היכן שנדרש, והדגשת מושגים מרכזיים. הימנע מהעמסת טקסט — כל שקף צריך להכיל רעיון מרכזי אחד בצורה ממוקדת וברורה.

הוסף שקף פתיחה עם מטרות למידה, שקפי סיכום לכל פרק מרכזי, ושקף סיום הכולל שאלות לדיון כיתתי.
```

English
```
Based on the academic document created in the previous step, generate a classroom training presentation.

The presentation should be pedagogically structured and clearly organized into slides according to the main chapters of the document. Each slide must include a clear title, concise bullet points, relevant examples where appropriate, and highlighted key concepts. Avoid excessive text—each slide should focus on one central idea presented clearly and succinctly.

Include an opening slide with learning objectives, summary slides for each major section, and a final slide with discussion questions for classroom engagement.
```

Review the Copilot suggestion and generate the presentation.


> Important
> 
> You must have permission to access the files you're referencing, whether they're located in your organization's SharePoint or OneDrive and can be either Word or PowerPoint files.

### Best practices when creating a presentation from a Word document

Leverage **Word Styles** to help Copilot understand the structure of your document. By using **Styles** in Word to organize your document, Copilot will better understand your document structure and how to break it up into slides of a presentation. Structure your content under **Titles** and **Headers** when appropriate and Copilot will do its best to generate a presentation for you.

### Include images that are relevant to your presentation

When creating a presentation, Copilot will try to incorporate the images in your Word document. If you have images that you would like to be brought over to your presentation, be sure to include them in your Word document.

### Start with your organization’s template

If your organization uses a standard template, start with this file before creating a presentation with Copilot. Starting with a template will let Copilot know that you would like to retain the presentation’s theme and design. Copilot will use existing layouts to build a presentation for you.