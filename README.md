Script-JS-Formulario-ProgAvanzada-UADER-2013
============================================

Este script en JS devuelve los vlores cargados en un formulario

<html>
   <head>
      <title>
         P&aacute;gina con Javascript.
      </title>
      <script language="javascript">
         <!--
            function comprobar()
            {
               var resultado = "";
               for (indice=0;indice<formulario.elements.length;indice++)
               {
                  resultado += "El campo " + indice + " se llama ";
                  resultado += formulario.elements[indice].name;
                  resultado += ". Es de tipo " + formulario.elements[indice].type;
                  resultado += ". Su valor es " + formulario.elements[indice].value;
                  resultado += "\n";
               }

               alert (resultado);

            }

         //-->
      </script>

