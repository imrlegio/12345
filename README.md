
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        img{
            width: 80%  ;
        }

        p{
            text-align: justify;
        }
    </style>
  </head>
  <body>
        <div>
            <div class="row">
          
                    <div class=" col-12 col-lg-6">
                        <h1>Indie Horror Games of 2025</h1>
            
                                        
                            <p> <b> Directive 8020</b> is the latest entry in The Dark Pictures Anthology and introduces a terrifying sci-fi horror setting. Set aboard the spaceship Cassiopeia, the game follows a crew sent to explore planet Tau Ceti F, only to encounter an unknown alien organism that begins to take control. As paranoia spreads among the crew, players must make critical choices that determine who survives and who falls victim to the extraterrestrial threat. With Supermassive Games’ signature cinematic approach, branching narratives, and immersive horror elements, Directive 8020 offers a chilling deep-space experience reminiscent of films like Alien and Event Horizon.</p>
            
                            <button><a href="https://store.steampowered.com/app/2255370/Directive_8020/">Buy Now on Steam!</a></button>
                            <button id="tombol">Notify Future Updates</button>

                            <script>
                              let tombol = document.letElementById('tombol');

                              tombol.addEventListener('click', function() {alert('Tombol diklik!'); 
                            });
                            </script>

                            <br><br>
                    </div >
                    <div class="col-12 col-lg-6">
                        <img src="D80201.jpg" alt="">
                    </div>
                
            </div>
        </div>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
