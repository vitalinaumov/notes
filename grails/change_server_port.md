1. Изменить grails.serverURL в файле Config.groovy 
с "http://localhost:8080/${appName}"
на "http://localhost:8090/${appName}".

1. Запустить grails с опцией -Dgrails.server.port.http=8090, либо дописать в
опцию GRAILS_OPT.

1. Добавить строку:
grails.server.port.http=8090 в файл BuildConfig.groovy.

1. Запустить grails с опцией -Dserver.port=8080
