 <div class="card-header"><h4>Request a Quote</h4></div>
 <form action="<?php echo htmlspecialchars($_SERVER['PHP_SELF']); ?>" method="post">
               
        		<input type="text" class="form-control" name="nombre" id="nombre" placeholder="Name" value="<?php if(!$enviado && isset($nombre)) echo $nombre ?>">
               
           		<input type="text" class="form-control" name="localidad" id="localidad" placeholder="Location" value="<?php if(!$enviado && isset($localidad)) echo $localidad ?>">

           		<input type="email" class="form-control" name="correo" id="correo" placeholder="E-mail" value="<?php if(!$enviado && isset($correo)) echo $correo ?>">
           		<textarea name="mensaje" class="form-control" id="mensaje" placeholder="Message:"><?php if(!$enviado && isset($mensaje)) echo $mensaje ?></textarea>


             <?php if (!empty($errores)): ?>
             	<div class="alert error">
             		<?php echo $errores; ?>
             	</div>
             <?php elseif($enviado): ?>
             	<div class="alert success">
             		<p>Your request has been sent successfully!</p>
             	</div>
             <?php endif ?>

               <input type="submit" name="submit" class="btn btn-secondary" value="Send Request">
     </form>
