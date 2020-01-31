---
layout: essay
type: essay
title: Is This Question Really Worth Asking? 
# All dates must be YYYY-MM-DD format!
date: 2020-01-30
labels:
  - Software Engineering 
  - Stackoverflow 
  - Asking questions 
---

##Too scared to ask questions.
  In class there are many horror stories about teachers shutting down students for asking questions about the material they have trouble understanding. The students suddenly get scared or nervous to ask questions when they are confused so their would grade start to go down hill. When I was a tutor for the lower level ICS courses, I dealt with students asking "whats wrong with my code" and they would show me the errors in the command line. Helping the students fix their code took longer than expected since I would have to look through the assignment to understand what the problem is. If the student summarized the assignment before they ask the question, it would be easier to assist them in fixing their error. There are right ways and wrong ways for a question to be phrase but it is a good idea to think about how you ask the question. 
  
##Rushed tomatoes? 
  Programmers use sites such as Stackoverflow to ask programming questions or to find solutions to their programming problems. When you are faced with a problem, you should search google first before asking a question in the forum. Most likely there was someone out there who had the same problem and the answer could be found in your google search. When asking a question in the forum you want to have a meaniful subject header, clear yet detailed explanation of your problem and have a explicit question. One example of a question I found in Stackoverflow had a semi- meaningful header "Get the result of the method and save it to a variable". However, their question stated "There is such code, I pass two parameters to the input and get the result of this method in the console, I need to save the result in a variable and pass it to another method how to do it right? Please do not rush tomatoes with a beginner in programming, I will be glad to any help. The result of the screen method enter image description here". They explained brefily what they needed to do but their question was not an explict question. The user should always proof read their questions before submitting them to make sure it is clear to the reader. Also, it is good to keep the statments professional and not use sayings like "Please do not rush tomatoes with a beginner in programming".
  
##Smart or great questions! 
```js 
public class ImagePanel extends JPanel{ 
  private Image img; 
  public ImagePanel(String img){ 
    this(new ImageIcon(img).getImage()); 
  }
  public ImagePanel(Image imf){ 
    this.img = img;
    //set layout size here 
  } 
  public paintComponent(Graphics g){ 
    g.drawImage(img, 0, 0, null); 
  } 
} 
```
