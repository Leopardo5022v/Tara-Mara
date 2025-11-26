TareaMara

String mensaje="Color elegido: ";
        
        if (optRojo.isSelected()) {
            mensaje=mensaje+"Rojo";
        } else if (optVerde.isSelected()) {
            mensaje=mensaje+"Verde";
        } else if (optAzul.isSelected()) {
            mensaje=mensaje+"Azul";
        }
        
        etiResultado.setText(mensaje);
     
