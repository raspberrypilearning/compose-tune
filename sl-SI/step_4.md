## Ponovi zvonjenje

Hišni zvonci pogosto ponavljajo melodijo.

+ Postavimo napev zvonca v zanko:
    
    ![posnetek zaslona](images/tune-times.png)
    
    Sonic Pi bo v pomoč zamaknil kodo hišnega zvonca v zanki `times`.

+ Prisluhni melodiji. Je to tisto pričakovano?
    
    Treba je na koncu dodati še vrstico `sleep`, ki ustvari pavzo pred ponavljanjem:
    
    ![posnetek zaslona](images/tune-sleep2.png)

+ Še enkrat poslušaj melodijo. Sedaj bi morala zveneti bolje.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/doorbell-2.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>