---
title: "Tutorial"
output: 
  learnr::tutorial:
    css: ["css/style.css"]
runtime: shiny_prerendered
---




## Topic 1

<details>
  <summary>Click to reveal code!</summary>


```
## [1] "hi"
```

</details>


:::puzzle
Tasks  
:::

:::fyi
FYI
:::

:::demo
Demo
:::


<details>
  <summary>Click for a tip!</summary>

:::note
Note
:::

</details>



### Exercise 

*Here's a simple exercise with an empty code chunk provided for entering the answer.*

Write the R code required to add two plus two:

<div class="tutorial-exercise" data-label="two-plus-two" data-caption="Code" data-completion="1" data-diagnostics="1" data-startover="1" data-lines="0"><script type="application/json" data-opts-chunk="1">{"fig.width":6.5,"fig.height":4,"fig.retina":2,"fig.align":"default","fig.keep":"high","fig.show":"asis","out.width":624,"warning":true,"error":false,"message":true,"exercise.df_print":"paged","exercise.checker":"NULL"}</script></div>

### Exercise with Code

*Here's an exercise with some prepopulated code as well as `exercise.lines = 5` to provide a bit more initial room to work.*

Now write a function that adds any two numbers and then call it:

<div class="tutorial-exercise" data-label="add-function" data-caption="Code" data-completion="1" data-diagnostics="1" data-startover="1" data-lines="5">

```text
add <- function() {
  
}
```

<script type="application/json" data-opts-chunk="1">{"fig.width":6.5,"fig.height":4,"fig.retina":2,"fig.align":"default","fig.keep":"high","fig.show":"asis","out.width":624,"warning":true,"error":false,"message":true,"exercise.df_print":"paged","exercise.checker":"NULL"}</script></div>

## Topic 2

### Exercise with Hint

*Here's an exercise where the chunk is pre-evaulated via the `exercise.eval` option (so the user can see the default output we'd like them to customize). We also add a "hint" to the correct solution via the chunk immediate below labeled `print-limit-hint`.*

Modify the following code to limit the number of rows printed to 5:

<div class="tutorial-exercise" data-label="print-limit" data-caption="Code" data-completion="1" data-diagnostics="1" data-startover="1" data-lines="0">

```text
mtcars
```

<div data-pagedtable="false">
  <script data-pagedtable-source type="application/json">
{"columns":[{"label":[""],"name":["_rn_"],"type":[""],"align":["left"]},{"label":["mpg"],"name":[1],"type":["dbl"],"align":["right"]},{"label":["cyl"],"name":[2],"type":["dbl"],"align":["right"]},{"label":["disp"],"name":[3],"type":["dbl"],"align":["right"]},{"label":["hp"],"name":[4],"type":["dbl"],"align":["right"]},{"label":["drat"],"name":[5],"type":["dbl"],"align":["right"]},{"label":["wt"],"name":[6],"type":["dbl"],"align":["right"]},{"label":["qsec"],"name":[7],"type":["dbl"],"align":["right"]},{"label":["vs"],"name":[8],"type":["dbl"],"align":["right"]},{"label":["am"],"name":[9],"type":["dbl"],"align":["right"]},{"label":["gear"],"name":[10],"type":["dbl"],"align":["right"]},{"label":["carb"],"name":[11],"type":["dbl"],"align":["right"]}],"data":[{"1":"21.0","2":"6","3":"160.0","4":"110","5":"3.90","6":"2.620","7":"16.46","8":"0","9":"1","10":"4","11":"4","_rn_":"Mazda RX4"},{"1":"21.0","2":"6","3":"160.0","4":"110","5":"3.90","6":"2.875","7":"17.02","8":"0","9":"1","10":"4","11":"4","_rn_":"Mazda RX4 Wag"},{"1":"22.8","2":"4","3":"108.0","4":"93","5":"3.85","6":"2.320","7":"18.61","8":"1","9":"1","10":"4","11":"1","_rn_":"Datsun 710"},{"1":"21.4","2":"6","3":"258.0","4":"110","5":"3.08","6":"3.215","7":"19.44","8":"1","9":"0","10":"3","11":"1","_rn_":"Hornet 4 Drive"},{"1":"18.7","2":"8","3":"360.0","4":"175","5":"3.15","6":"3.440","7":"17.02","8":"0","9":"0","10":"3","11":"2","_rn_":"Hornet Sportabout"},{"1":"18.1","2":"6","3":"225.0","4":"105","5":"2.76","6":"3.460","7":"20.22","8":"1","9":"0","10":"3","11":"1","_rn_":"Valiant"},{"1":"14.3","2":"8","3":"360.0","4":"245","5":"3.21","6":"3.570","7":"15.84","8":"0","9":"0","10":"3","11":"4","_rn_":"Duster 360"},{"1":"24.4","2":"4","3":"146.7","4":"62","5":"3.69","6":"3.190","7":"20.00","8":"1","9":"0","10":"4","11":"2","_rn_":"Merc 240D"},{"1":"22.8","2":"4","3":"140.8","4":"95","5":"3.92","6":"3.150","7":"22.90","8":"1","9":"0","10":"4","11":"2","_rn_":"Merc 230"},{"1":"19.2","2":"6","3":"167.6","4":"123","5":"3.92","6":"3.440","7":"18.30","8":"1","9":"0","10":"4","11":"4","_rn_":"Merc 280"},{"1":"17.8","2":"6","3":"167.6","4":"123","5":"3.92","6":"3.440","7":"18.90","8":"1","9":"0","10":"4","11":"4","_rn_":"Merc 280C"},{"1":"16.4","2":"8","3":"275.8","4":"180","5":"3.07","6":"4.070","7":"17.40","8":"0","9":"0","10":"3","11":"3","_rn_":"Merc 450SE"},{"1":"17.3","2":"8","3":"275.8","4":"180","5":"3.07","6":"3.730","7":"17.60","8":"0","9":"0","10":"3","11":"3","_rn_":"Merc 450SL"},{"1":"15.2","2":"8","3":"275.8","4":"180","5":"3.07","6":"3.780","7":"18.00","8":"0","9":"0","10":"3","11":"3","_rn_":"Merc 450SLC"},{"1":"10.4","2":"8","3":"472.0","4":"205","5":"2.93","6":"5.250","7":"17.98","8":"0","9":"0","10":"3","11":"4","_rn_":"Cadillac Fleetwood"},{"1":"10.4","2":"8","3":"460.0","4":"215","5":"3.00","6":"5.424","7":"17.82","8":"0","9":"0","10":"3","11":"4","_rn_":"Lincoln Continental"},{"1":"14.7","2":"8","3":"440.0","4":"230","5":"3.23","6":"5.345","7":"17.42","8":"0","9":"0","10":"3","11":"4","_rn_":"Chrysler Imperial"},{"1":"32.4","2":"4","3":"78.7","4":"66","5":"4.08","6":"2.200","7":"19.47","8":"1","9":"1","10":"4","11":"1","_rn_":"Fiat 128"},{"1":"30.4","2":"4","3":"75.7","4":"52","5":"4.93","6":"1.615","7":"18.52","8":"1","9":"1","10":"4","11":"2","_rn_":"Honda Civic"},{"1":"33.9","2":"4","3":"71.1","4":"65","5":"4.22","6":"1.835","7":"19.90","8":"1","9":"1","10":"4","11":"1","_rn_":"Toyota Corolla"},{"1":"21.5","2":"4","3":"120.1","4":"97","5":"3.70","6":"2.465","7":"20.01","8":"1","9":"0","10":"3","11":"1","_rn_":"Toyota Corona"},{"1":"15.5","2":"8","3":"318.0","4":"150","5":"2.76","6":"3.520","7":"16.87","8":"0","9":"0","10":"3","11":"2","_rn_":"Dodge Challenger"},{"1":"15.2","2":"8","3":"304.0","4":"150","5":"3.15","6":"3.435","7":"17.30","8":"0","9":"0","10":"3","11":"2","_rn_":"AMC Javelin"},{"1":"13.3","2":"8","3":"350.0","4":"245","5":"3.73","6":"3.840","7":"15.41","8":"0","9":"0","10":"3","11":"4","_rn_":"Camaro Z28"},{"1":"19.2","2":"8","3":"400.0","4":"175","5":"3.08","6":"3.845","7":"17.05","8":"0","9":"0","10":"3","11":"2","_rn_":"Pontiac Firebird"},{"1":"27.3","2":"4","3":"79.0","4":"66","5":"4.08","6":"1.935","7":"18.90","8":"1","9":"1","10":"4","11":"1","_rn_":"Fiat X1-9"},{"1":"26.0","2":"4","3":"120.3","4":"91","5":"4.43","6":"2.140","7":"16.70","8":"0","9":"1","10":"5","11":"2","_rn_":"Porsche 914-2"},{"1":"30.4","2":"4","3":"95.1","4":"113","5":"3.77","6":"1.513","7":"16.90","8":"1","9":"1","10":"5","11":"2","_rn_":"Lotus Europa"},{"1":"15.8","2":"8","3":"351.0","4":"264","5":"4.22","6":"3.170","7":"14.50","8":"0","9":"1","10":"5","11":"4","_rn_":"Ford Pantera L"},{"1":"19.7","2":"6","3":"145.0","4":"175","5":"3.62","6":"2.770","7":"15.50","8":"0","9":"1","10":"5","11":"6","_rn_":"Ferrari Dino"},{"1":"15.0","2":"8","3":"301.0","4":"335","5":"3.54","6":"3.570","7":"14.60","8":"0","9":"1","10":"5","11":"8","_rn_":"Maserati Bora"},{"1":"21.4","2":"4","3":"121.0","4":"109","5":"4.11","6":"2.780","7":"18.60","8":"1","9":"1","10":"4","11":"2","_rn_":"Volvo 142E"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>
</div><script type="application/json" data-opts-chunk="1">{"fig.width":6.5,"fig.height":4,"fig.retina":2,"fig.align":"default","fig.keep":"high","fig.show":"asis","out.width":624,"warning":true,"error":false,"message":true,"exercise.df_print":"paged","exercise.checker":"NULL"}</script></div>

<div class="tutorial-exercise-support" data-label="print-limit-hint" data-caption="Code" data-completion="1" data-diagnostics="1" data-startover="1" data-lines="0">

```text
head(mtcars)
```

</div>

### Quiz

*You can include any number of single or multiple choice questions as a quiz. Use the `question` function to define a question and the `quiz` function for grouping multiple questions together.*

Some questions to verify that you understand the purposes of various base and recommended R packages:

<!--html_preserve--><div class="panel-heading tutorial-quiz-title">Quiz</div><!--/html_preserve--><!--html_preserve--><div class="panel panel-default">
<div data-label="quiz-1" class="tutorial-question panel-body">
<div id="quiz-1-answer_container" class="shiny-html-output"></div>
<div id="quiz-1-message_container" class="shiny-html-output"></div>
<div id="quiz-1-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve--><!--html_preserve--><div class="panel panel-default">
<div data-label="quiz-2" class="tutorial-question panel-body">
<div id="quiz-2-answer_container" class="shiny-html-output"></div>
<div id="quiz-2-message_container" class="shiny-html-output"></div>
<div id="quiz-2-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve-->

<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server-start">
library(learnr)
knitr::opts_chunk$set(echo = FALSE)
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::register_http_handlers(session, metadata = NULL)
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
session$onSessionEnded(function() {
        learnr:::session_stop_event(session)
      })
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
`tutorial-exercise-two-plus-two-result` <- learnr:::setup_exercise_handler(reactive(req(input$`tutorial-exercise-two-plus-two-code-editor`)), session)
output$`tutorial-exercise-two-plus-two-output` <- renderUI({
  `tutorial-exercise-two-plus-two-result`()
})
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
`tutorial-exercise-add-function-result` <- learnr:::setup_exercise_handler(reactive(req(input$`tutorial-exercise-add-function-code-editor`)), session)
output$`tutorial-exercise-add-function-output` <- renderUI({
  `tutorial-exercise-add-function-result`()
})
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
`tutorial-exercise-print-limit-result` <- learnr:::setup_exercise_handler(reactive(req(input$`tutorial-exercise-print-limit-code-editor`)), session)
output$`tutorial-exercise-print-limit-output` <- renderUI({
  `tutorial-exercise-print-limit-result`()
})
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_radio", label = "quiz-1", question = structure("Which package contains functions for installing other R packages?", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_5b95346",     option = "base", value = "base", label = structure("base", html = TRUE, class = c("html",     "character")), correct = FALSE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_e521f69",     option = "tools", value = "tools", label = structure("tools", html = TRUE, class = c("html",     "character")), correct = FALSE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_34f0c28",     option = "utils", value = "utils", label = structure("utils", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_9686316",     option = "codetools", value = "codetools", label = structure("codetools", html = TRUE, class = c("html",     "character")), correct = FALSE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "quiz-1-answer", question = "quiz-1"), loading = structure("<strong>Loading:<\u002fstrong> \nWhich package contains functions for installing other R packages?\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = FALSE, allow_retry = FALSE,     seed = 2121306782.01219, options = list()), class = c("learnr_radio", "tutorial_question")))
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_checkbox", label = "quiz-2", question = structure("Which of the R packages listed below are used to create plots?", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_5b164fd",     option = "lattice", value = "lattice", label = structure("lattice", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_873a68e",     option = "tools", value = "tools", label = structure("tools", html = TRUE, class = c("html",     "character")), correct = FALSE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_a96737f",     option = "stats", value = "stats", label = structure("stats", html = TRUE, class = c("html",     "character")), correct = FALSE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_14cbc7f",     option = "grid", value = "grid", label = structure("grid", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "quiz-2-answer", question = "quiz-2"), loading = structure("<strong>Loading:<\u002fstrong> \nWhich of the R packages listed below are used to create plots?\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = FALSE, allow_retry = FALSE,     seed = 1210491452.43632, options = list()), class = c("learnr_checkbox", "tutorial_question")))
</script>
<!--/html_preserve-->
