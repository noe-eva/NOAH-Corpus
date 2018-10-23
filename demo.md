
   <h1>Swiss German  Part-of-Speech Tagging Demo</h1>
<form action="https://pub.cl.uzh.ch/demo/noah/wapiti.cgi" method="POST" accept-charset="UTF-8" name="FormName" target="resultat">
 

                <fieldset>
                    <input class="btn btn-outline-success" type="submit" value="Analyze" name="submitButtonName">
                    <legend>Input </legend>
                    <textarea name="t" style="width:100%" rows="12" cols="120">Das isch es Bispiili mitem Wort Chuchichäschtli drin .</textarea>
                    Format: words separated by white-space
                </fieldset>

       
                <fieldset>
                    <legend>Output</legend>
                    <iframe style="width:100%  " name="resultat" id="resultat" onLoad="autoResize('resultat');" src="denada.md" marginwidth="0" marginheight="0" align="left" scrolling="yes" >
                        <p>Your browser does not support  frames, sorry!</p>
                    </iframe>
                </fieldset>
      
</form>

