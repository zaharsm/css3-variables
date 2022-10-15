# css3-variables


          .final-result {
            --primary-color: orangered;
            --secondary-color: hotpink;
            --base-measurement: 20px;
          }


          .final-result .final__box {
            text-align: center;


            --text-color: #f3f3f3;
            color: var(--text-color);

            background: var(--primary-color);
            margin:     var(--base-measurement);


            height:       calc( var(--base-measurement) * 10 );
            width:        calc( var(--base-measurement) * 10 );
            line-height:  calc( var(--base-measurement) * 10 );
          }

          .final-result .final__box2 {
            background: var(--secondary-color);
          }
          
<hr>
         
<img src="variables.png">
