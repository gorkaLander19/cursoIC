# maven

# creacion de un nuevo proyecto java basada en una plantilla ( arquetipo )
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp
##identificadar un proyecto maven:
-groupID :
    -empresa / organizacion al cargo del desarrollo (dominio invertido)
        -ejm: com.gfi
    -que estoy desarrrollando ? 
        -web-app-nominas
        
-com.gfi.web-app-nominas -> groupId

-artifactID : que es nuestro proyecto a bajo nivel?
    -ejemplo:     -web-services
el identificadar de un proyecto es groupID + artifactID

# goles
mvn GOLE_NAME 
    -compile: compilacion del proyecto
    -test-compile : compilar los test unitarios 
    -test : ejecutar todas las pruebas unitarias
    -package : empaquetar proyecto
    -install : inlcuir nuestro artefacto en nuestro repositorio
    
    # Ejecutrar comandos dentro de un conteneder
        docker exec CONTENEDOR COMANDO
        docker exec -it CONTENEDOR COMANDO
        #copiar archivos entre conteneder y host
        docker cp ORIGEN DESTINO
            tanto en origen como destino puedo preceder al ruta de "CONTENEDOR:"
            Ejemplo: docker cp mitomcat:/etc/configuration ./configcopiada
            Ejemplo: docker cp ./configcopiada mitomcat:/etc/configuration 
            
            
    