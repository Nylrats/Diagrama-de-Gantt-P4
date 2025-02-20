# Diagrama-de-Gantt-P4
En este podremos clasificarnos las tareas del proyecto en cuanto fecha de inicio, fecha de finalización y dividirnos el trabajo de manera eficiente.
```mermaid
gantt
    title Proyecto 4
    dateFormat YYYY-MM-DD

    section Gestión del proyecto
    Acta de constitución                       :done,    des1, 2025-02-21, 5d
    Diagrama de Gantt                          :active,  des2, 2025-02-25, 3d
    Gester de contenidos                       :         des3, 2025-02-28, 7d
    PLE                                        :         des4, 2025-03-06, 5d

    section Equipos informaticos
    Componentes y recanvios                                           :done,    des1, 2025-02-20, 5d
    Análisis de la BIOS                                               :active,  des2, 2025-02-25, 3d
    Protocolos de reparación de averías I averías en el hardware      :         des3, 2025-02-28, 7d
    Prevención de riesgos - Equipos informáticos                      :         des4, 2025-03-06, 5d
    Gestión de residuos - Equipos informáticos                        :         des4, 2025-03-06, 5d

    section Redes
    Redes inalámbricas                                                :done,    des1, 2025-02-20, 5d
    Protocolos de reparación de averías II averías en la red          :active,  des2, 2025-02-25, 10d
    Prevención de riesgos - Redes                                     :         des3, 2025-02-28, 7d
    Gestión de residuos - Redes                                       :         des4, 2025-03-06, 5d

    section Sistema operativo y software                              
    Sistemas operativos                                               :done,    des1, 2025-02-20, 5d
    Aplicaciones                                                      :active,  des2, 2025-02-25, 3d

    section La web
    El servicio FTP                                                   :done,    des1, 2025-02-20, 5d
    La web                                                            :active,  des2, 2025-02-25, 3d
    Base de datos                                                     :         des3, 2025-02-28, 7d
    Sistema de tickets                                                :         des4, 2025-03-06, 5d
    Vídeo tutoriales de reparación de averías                         :         des4, 2025-03-06, 5d
    Helpdesk                                                          :         des4, 2025-03-06, 5d

    section Recursos Humanos (RRHH) 
    CV en inglés                                                      :done,    des1, 2025-02-20, 5d
    Convenio colectivo                                                :active,  des2, 2025-02-25, 3d
    Plan de prevención de riesgos laborales                           :         des3, 2025-02-28, 7d
    Entrevista de trabajo (inglés)                                    :         des4, 2025-03-06, 5d

    section  Gestión documental 
    La memoria                                                         :done,    des1, 2025-02-20, 5d
    La presentación                                                    :active,  des2, 2025-02-25, 3d

