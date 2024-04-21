# Read-More-Less-Button-
 <a href="#" class="btn" onclick="readmore1(event)" >Read More</a>
                    <script>
                        function readmore1(event) {
                            event.preventDefault();
                          var moretext = document.querySelector('.text .moretext');
                          var btn = document.querySelector('.text .btn');
                          if (moretext.style.display === 'none' || moretext.style.display==='') {
                            moretext.style.display = 'block';
                            btn.innerText = 'Read Less';
                    } else {
                            moretext.style.display = 'none';
                            btn.innerText = 'Read More';
                          }
                        }
                        </script> </div></div>
