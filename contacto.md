---
layout: index
title: Clinica de medicina tradicional Atekokolli
tagline: Bootstrap 4 UI kit for Jekyll
css: contacto.css
js: 
keywords: helium, jekyll, bootstrap, UI, kit
canonical: https://heliumjk.github.io
---
{% include JB/setup %}
<!-- Content Area Start -->
<div id="content">
      <div class="mb-60"></div>   
      <!-- CONTACT FORM -->     
	<div class="container">
	<div class="row">	      
          <div class="col-md-8">
            <h3 class="title-head text-center">Contactanos</h3>
            <form class="contact-form" data-toggle="validator">
              <div class="row">
                <div class="col-sm-4">
                  <div class="form-group">
                    <i class="contact-icon fa fa-user"></i>
                    <input type="text" class="form-control" id="name" placeholder="Nombre completo" required data-error="Ingrese su nombre">
                    <div class="help-block with-errors"></div>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="form-group">
                    <i class="contact-icon fa fa-envelope-o"></i>
                    <input type="email" class="form-control" id="email" placeholder="Email" required data-error="Ingrese su email">
                    <div class="help-block with-errors"></div>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="form-group">
                    <i class="contact-icon fa fa-pencil-square-o"></i>
                    <input type="text" class="form-control" id="subject" placeholder="Tema" required data-error="Ingrese el tema">
                    <div class="help-block with-errors"></div>
                  </div>
                </div>
                <div class="col-sm-12">
                  <div class="form-group">
                    <textarea id="message" rows="8" placeholder="Mensaje" required data-error="Escriba su mensaje"></textarea>
                    <div class="help-block with-errors"></div>
                  </div>
                  <button type="submit" id="form-submit" class="btn btn-common btn-form-submit">Mandar mensaje</button>
                  <div id="msgSubmit" class="h3 text-center hidden"></div>
                  <div class="clearfix"></div>
                </div>
              </div>
            </form>
          </div>
          <div class="col-md-4">
            <h4 class="contact-info-title">Information de Contacto</h4>
            <div class="contact-info">
              <address>
							<i class="fa fa-map-marker icons cyan-color contact-info-icon"></i>
							Calle Tepepexpan s/n esq. 20 de Noviembre,
							<br>
							Amatlán de Quetzalcoatl, Municipio de Tepoztlán,
              Morelos, Mexico C.P. 62525  
						</address>
              <div class="tel-info">
                <a href="tel:+52(1739)3933194"><i class="fa fa-phone icons cyan-color contact-info-icon"></i>01(739)3933194</a>
              </div>
              <a href="mailto:contacto@atekokolli.org"><i class="fa fa-envelope-o icons cyan-color contact-info-icon"></i>contacto@atekokolli.org</a>
              <div><strong>Horarios</strong></div>
              <ul class="horarios">
                <li>Lunes: Cerrado</li>
                <li>Martes: 10:30am-5:00pm</li>
                <li>Miercoles: Cerrado</li>
                <li>Jueves: 10:30am-5:00pm</li>
                <li>Viernes: 10:30am-5:00pm</li>
                <li>Sabado: 9:00am-2:00pm</li>
                <li>Domingo: Cerrado</li>
              </ul>
              <!-- {% include social-block.html %} -->
              <img src="assets/images/guiacomollegar.jpg" >
              <img src="assets/images/bienvenidos_por_la_carretera.jpg" >
            </div>
          </div>

        </div>
	</div>

            
            
<!-- Content area end -->
</div>
