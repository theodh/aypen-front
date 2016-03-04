---
layout: page
title: Contact
description: contact opnemen met Aypen
keywords: contact opnemen
author: Theo den Hollander
---
<div class="row">
    <div class="main-column col-12">
        
        <iframe width="100%" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="http://www.openstreetmap.org/export/embed.html?bbox=5.866779685020447%2C51.72640014962429%2C5.870427489280701%2C51.728413729868855&amp;layer=mapnik&amp;marker=51.727406950958%2C5.868603587150574" style="border: 1px solid black"></iframe><br/><small><a href="http://www.openstreetmap.org/?mlat=51.72741&amp;mlon=5.86860#map=18/51.72741/5.86860">Grotere kaart bekijken</a></small>
        
        <div class="inner">
            <div class="row">
                <div class="col-12">
                    <h3>Contact</h3>
                    <p>Heeft u vragen, opmerkingen of wilt u een offerte aanvragen, neem dan contact op via onderstaand formulier.</p>
                     <hr>
                    <form id="contact-form" action="send.php" method="post">
                        <div class="form-group">
                            <label for="firstname">Voornaam <span class="form-required" title="This field is required.">*</span></label>
                            <input type="text" name="firstname" class="form-control half" id="firstname" required>
                        </div>
                        <div class="form-group">
                            <label for="lastname">Achternaam <span class="form-required" title="This field is required.">*</span></label>
                            <input type="text" name="lastname" class="form-control half" id="lastname" required>
                        </div>
                        <div class="form-group">
                            <label for="email">E-mail <span class="form-required" title="This field is required.">*</span></label>
                            <input type="email" name="email" class="form-control half" id="email" required>
                        </div>
                        <div class="form-group">
                            <label for="subject">Onderwerp</label>
                            <input type="text" name="subject" class="form-control half" id="subject">
                        </div>
                        <div class="form-group">
                            <label for="message">Bericht <span class="form-required" title="This field is required.">*</span></label>
                            <textarea name="message" class="form-control" rows="4" id="message" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-color"><i class="glyphicon glyphicon-send"></i>Verstuur</button>
                    </form>
                </div>
               
            </div>
        </div>
    </div>
</div>