<<template>
    <section>
        <div class="span">
            
            <img src="~assets/BBFF.jpg" style="width=100%; height=100%;">
        </div>
        <div>
         
  <input id="toggle" type="checkbox" checked>
  <label for="toggle">About</label>
  <div id="expand">
    <section>
         <p>
            This event is based on Business strategy and Marketing techniques. This event will help you to polish your Promotion as well as Selling skills. It will also give you the experience of Field work in Marketing Area. The Winner as well as Participants of this event will get an ISTE Certificate.
          </p>
     </section>
  </div>
  </div>
  <div>
  <input id="toggle1" type="checkbox" unchecked>
  <label for="toggle1">Rules</label>
  <div id="expand">
    <section>
         <ol>
            <li>Participants must be on time.</li>
            <li>Vulgar and unruly behavior will not be tolerated.</li>
            <li>Elimination is based on judging criteria.</li></br>
            <p><b>Round 1 - Biz Quiz</b><i></i></br>
              The Excitement of this even will start form Mind Game. Here one slide show will be shown to the participants and regarding to that slideshow questions will be asked. It will be pen-paper based task.</br>
              <b>Round 2 – Monopoly</b><i></i></br>
              In second round a kit will be provided to the participants. The participants have to sell the items provided in that kit with maximum profit. This round evaluates the convincing and bargaining skills of the participants.</br>
              <b>Round 3- Market Maniac</b><i></i><br>
               Surprise Round (Hint :- Live Marketing).</br>
            </p>
          </ol>
     </section>
  </div>
  </div>
  <div>
  <input id="toggle2" type="checkbox" unchecked>
  <label for="toggle2">Contact</label>
  <div id="expand">
    <section>
      <p>
        <li>Jigar Rabadiya: +918238431186</li>
      <li>Event Joint Head: +917984275781</li>
        
      </p>
      </section>
  </div>
  </div>
  </div>
  
    </section>
</template>>

<style scoped>
 
@import url(https://fonts.googleapis.com/css?family=Open+Sans:400,700);

body {
  font-family: "Open Sans", Arial;
  background: #CCC;
  justify-content: center;
}
main {
  background: #EEE;
  width: 600px;
  margin: 20px auto;
  padding: 10px 0;
  box-shadow: 0 3px 5px rgba(0,0,0,0.3);
 
}
desc{
    display: flex;
    justify-content: center;
    align-items: center;
}
.span {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding-top: 10px;
  padding-bottom: 10px;


}
h2 {
  text-align: center;
  justify-content: center;
  font-size: 25px;
}
p {
  font-size: 20px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
li{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size: 18px;
}
ol{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
input {
  display: none;
  visibility: hidden;
}
label {
  display: flex;
  padding: 0.5em;
  text-align: center;
  border-bottom: 1px solid #CCC;
  color: #666;
  justify-content: center;
  font-size: 25px;
}
label:hover {
  color: #000;
}
label::before {
  font-family: Consolas, monaco, monospace;
  font-weight: bold;
  font-size: 15px;
  content: "+";
  vertical-align: text-top;
  display: inline-block;
  width: 20px;
  height: 20px;
  margin-right: 3px;
  background: radial-gradient(ellipse at center #e3e3e3 50%, transparent 50%);
}
#expand {
  height: 0px;
  overflow: hidden;
  transition: height 0.5s;
  
  
}

section {
  padding: 0 20px;
}
#toggle:checked ~ #expand {
  height: 100px;
}
#toggle:checked ~ label::before {
  content: "-";
}
#toggle1:checked ~ #expand {
  height: 350px;
}
#toggle1:checked ~ label::before {
  content: "-";
}
#toggle2:checked ~ #expand {
  height: 100px;
}
#toggle2:checked ~ label::before {
  content: "-";
}
@media only screen and (max-width: 420px){
  #toggle:checked ~ #expand {
  height: 280px;
}
#toggle:checked ~ label::before {
  content: "-";
}
#toggle1:checked ~ #expand {
  height: 660px;
}
#toggle1:checked ~ label::before {
  content: "-";
}

}
@media only screen and (max-width: 375px){
  #toggle:checked ~ #expand {
  height: 300px;
}
#toggle:checked ~ label::before {
  content: "-";
}
#toggle1:checked ~ #expand {
  height: 750px;
}
#toggle1:checked ~ label::before {
  content: "-";
}

}
@media only screen and (max-width: 330px){
  #toggle:checked ~ #expand {
  height: 360px;
}
#toggle:checked ~ label::before {
  content: "-";
}
#toggle1:checked ~ #expand {
  height: 830px;
}
#toggle1:checked ~ label::before {
  content: "-";
}

}

</style>
>
