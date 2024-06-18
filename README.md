# Prompt Engineering Notes
* How to generate high quality output with ChatGPT?

## 6 key components (importance, top -> down = highest -> lowest)
* task (mandatory)
* context (important)
* exemplar (important)
* persona (nice to have)
* format (nice to have)
* tone (nice to have)

## Putting together:
* **persona** + **context** (background + success + environment) + **task** + **exemplar** + **format** + **tone**

E.g.:
* [context]:
  * [context:background] I am a 70 kb male
  * [context:success] looking to put on 5 kg of muscle mass over the next 3 months
  * [context:environment] I only have time to go to the gym twice a week and for a  1 hour session
* [task] 
  * Give me a 3 month program to follow
 
E.g:

**[persona]** You are a senior product marketing manager at Appple 
**[context]** and you have just unveiled the latest Apple product in collaboration with Tesla, the Apple car and received 12000 pre-orders, which is 200% higher than target.
**[task and format]** Write an email to your boss, Tim Cookie, sharing this positive news.
**[exemplar]** This email should include tldr (too long, didn't read) section, project background, (why this product came into existence), business results section (quantifiable business metrics), and end with a section thanking the product and engineering teams.
**[tone]** Use clear and concise language and write in a confident yet friendly tone

    
## Details
* Task
  * Start with a verb
    * E.g. generate, give, write, etc..   
  * State what the end goal is
    * One simple task
      * *Generate* a 3 month training program for me to follow
    * Multi-task
      * *Analyze* the collected user feedback from an event we just ran, *summarize* the top 3 takeaways with focus on business impact and *categorize* the rest based on team responsibility
* Context
  * Helpful context:
    * What is the user's *background*?
    * What does the *success* look like?
    * What *environment* are they in?
  * E.g.
    * <background>I am a 70 kb male
    * <success> looking to put on 5 kg of muscle mass over the next 3 months
    * <environment> I only have time to go to the gym twice a week and for a  1 hour session
    * <task> Give me a 3 month program to follow
* Examplars (Examples)
  * Examples increase the quality a lot
  * E.g. 
    * Rewrite the resume using this structure: 'I accomplished X by the measure Y that resulted Z'
    * E.g.: I lowered the hospital mortality rate by 10% by educating nurses in new protocols which translates to 200 lives saved per year
* Persona
  * Who do you want the AI to be?
  * E.g.: a physician, botanist etc ...
* Format
  * How the end result should be represented (visualized)
  * Use format and markdown
  * E.g.: Output in table format with column header: Feedback, Team, Priority
  * E.g.: Use H2 as section headers
  * E.g.: Bold all changes you make
* Tone
    * Give the feeling to ChatGPT
    * E.g. use a casual tone

 


    
