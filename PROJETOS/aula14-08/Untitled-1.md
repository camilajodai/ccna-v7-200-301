AULA 14/08/2023

cabo console num desktop, conecta no 2960 > porta console / 232 > terminal >>>
comandos:
    enable (habilitar)
    disable (desabilitar)
    enable > clock set (primeira coisa a se fr é config hr e data)
        Switch#clock set 14:18:00 14 August 2023
            configure terminal (sai da hashtag e aparece config)
            hostname (sw-l2-2960-1)
    service password-encryption (habilitar o servcuso de todo diqqa)
    sw-l2-2960-1(config)#service timestamps log datetime msec
    sw-l2-2960-1(config)#no ip domain-lookup
    sw-l2-2960-1(config)#banner motd #AVISO: acesso autorizado somente para funcionarios#
    sw-l2-2960-1(config)#enable secret 123@senac
    end
    sw-l2-2960-1#copy running-config startup-config 
    