# layoutxml
Apresentação sobre layout xml no Magento 2

Utilize o seguinte comando na raiz do projeto para clonar o tema

git clone git@github.com:erickwebjump/layoutxml.git app/design/frontend/

Após isso rode os comandos de Deploy

bin/magento setup:upgrade; 
bin/magento setup:di:compile;
bin/magento setup:static-content:deploy -f;
