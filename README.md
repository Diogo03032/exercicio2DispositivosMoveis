# exercicio2DispositivosMoveis

REVISAO PROGRAMAÇÃO PARA DISPOSITIVOS MOVEIS

Pode ser que caia naveação {
  3 tipos - tab, stack, drawer. Navegação ninhada (usando mais de uma junta).
  Possibilidade de passar parâmetros entre telas.
  useEffect versão foco. 
  rotação de tela.
}
temas (claro, escuro, sistema)

gerenciamento de estado {
  -useState: usado mais em telas pequenas.
  -useReducer: usado mais em projetos grandes. Separam variaveis em estados, conegue saber em que estado a tela está (se está no login, preenchendo um        campo, etc, separa em etapas)
  -Actions *
  -Hook *
  (revisar o que cada um faz)
}

Contexto da aplicação (context)
  Como se fosse a alma do aplicativo, uma coisa que fica por trás.
  Pode ter mais de um contexto

Armazenamento
  sync storage (chave, valor) - coisas objetivas
  
SQLite - banco mais lento (chave estrangeira desabilitada, so permite uma requisição por ves)  

Armazenamento 
  externo: dados sensíveis 
  interno:  aplicativo

Permissões - não pedir tudo de uma vez, não pedir novamente, não impedir de usar o aplicativo quando recusar uma permissão.

Sensores (GPS, WIFI, NFC, etc) nem todos os dispositivos tem todos os sensores
  podem não esar funcionando
  
Tests - (Piramide, em relação a quantidade)
  Unitários
  Integração
  Testes de API
  Testes de UI (Interface)
  E2E (end-to-end)
