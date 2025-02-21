# Diagrama-de-Gantt-P4
En este podremos clasificarnos las tareas del proyecto en cuanto fecha de inicio, fecha de finalización y dividirnos el trabajo de manera eficiente.

```mermaid
gantt
    title Proyecto 4
    dateFormat YYYY-MM-DD

    %% Tarea fantasma para definir el inicio
    "" : milestone, start1, 2025-02-03, 3d

    section Gestión del proyecto
    Acta de constitución                       :active,  des1, 2025-02-17, 1d
    Diagrama de Gantt                          :active,  des2, 2025-02-20, 1d
    Gester de contenidos                       :active,         des3, 2025-02-21, 4d
    PLE                                        :active,         des4, 2025-03-18, 1d

    section Equipos informaticos
    Componentes y recanvios                                           :active,         des5, 2025-02-24, 2d
    Análisis de la BIOS                                               :active,         des6, 2025-02-19, 39d
    Protocolos de reparación de averías I averías en el hardware      :active,         des7, 2025-02-25, 3d
    Prevención de riesgos - Equipos informáticos                      :active,         des8, 2025-02-27, 2d
    Gestión de residuos - Equipos informáticos                        :active,         des9, 2025-02-28, 2d

    section Redes
    Redes inalámbricas                                                :active,        des10, 2025-03-03, 1d
    Protocolos de reparación de averías II averías en la red          :active,        des11, 2025-03-04, 3d
    Prevención de riesgos - Redes                                     :active,        des12, 2025-03-05, 2d
    Gestión de residuos - Redes                                       :active,        des13, 2025-03-06, 2d

    section Sistema operativo y software                              
    Sistemas operativos                                               :active,         des14, 2025-03-03, 2d
    Aplicaciones                                                      :active,         des15, 2025-03-05, 2d
                
    section La web
    El servicio FTP                                                   :active,         des16, 2025-03-10, 2d
    La web                                                            :active,         des17, 2025-03-12, 3d
    Base de datos                                                     :active,         des18, 2025-03-11, 2d
    Sistema de tickets                                                :active,         des19, 2025-03-15, 4d
    Vídeo tutoriales de reparación de averías                         :active,         des20, 2025-03-17, 5d
    Helpdesk                                                          :active,         des21, 2025-03-24, 5d

    section Recursos Humanos (RRHH) 
    CV en inglés                                                      :active,         des22, 2025-02-21, 4d
    Convenio colectivo                                                :active,         des23, 2025-02-24, 2d
    Plan de prevención de riesgos laborales                           :active,         des23, 2025-02-25, 2d
    Entrevista de trabajo (inglés)                                    :active,         des24, 2025-03-24, 5d

    section  Gestión documental 
    La memoria                                                         :active,    des25, 2025-02-03, 39d
    La presentación                                                    :active,  des26, 2025-03-18, 3d

