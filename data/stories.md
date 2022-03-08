## saludo 1
* saludo
   - utter_saludo

## grafica serie 10
* grafica_serie{"tipo_grafica":"serie"}
    - slot{"tipo_grafica":"serie"}
    - utter_ask_senal
* grafica_serie{"tipo_grafica":"serie","senal":"cic0010"}
    - slot{"senal":"cic0010"}
    - slot{"tipo_grafica":"serie"}
    - utter_ask_tipo_serie
* mark{"mark_value":"no"}
    - slot{"mark_value":"no"}
    - action_grafica_serie
    - slot{"senal":null}
    - slot{"fecha":null}
    - slot{"mark_value":null}
    - slot{"tipo_grafica":null}
