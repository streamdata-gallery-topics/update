---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:actionTarget/{key}:
    put:
      summary: Create or update a chat:actionTarget module
      description: Authentication required, with scope participate:conversation
      operationId: AppModuleChatActionTargetPutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatactiontargetkey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:actionTarget
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:bot/{key}:
    put:
      summary: Create or update a chat:bot module
      description: Authentication required, with scope participate:conversation
      operationId: AppWebhookChatBotPutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatbotkey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:bot
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:bot:messages/{key}:
    put:
      summary: Create or update a chat:bot:messages module
      description: Authentication required, with scope participate:conversation
      operationId: AppWebhookChatBotMessagePutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatbotmessageskey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:bot:messages
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:dialog/{key}:
    put:
      summary: Create or update a chat:dialog module
      description: Authentication required, with scope participate:conversation
      operationId: AppModuleChatDialogPutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatdialogkey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:dialog
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:externalPage/{key}:
    put:
      summary: Create or update a chat:externalPage module
      description: Authentication required, with scope participate:conversation
      operationId: AppModuleChatExternalPagePutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatexternalpagekey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:externalPage
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:glance/{key}:
    put:
      summary: Create or update a chat:glance module
      description: Authentication required, with scope participate:conversation
      operationId: AppModuleChatGlancePutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatglancekey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:glance
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:sidebar/{key}:
    put:
      summary: Create or update a chat:sidebar module
      description: Authentication required, with scope participate:conversation
      operationId: AppModuleChatSidebarPutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatsidebarkey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:sidebar
      - Module
  /site/{cloudId}/conversation/{conversationId}/app/module/chat:webhook/{key}:
    put:
      summary: Create or update a chat:webhook module
      description: Authentication required, with scope participate:conversation
      operationId: AppWebhookChatWebhookPutHandler
      x-api-path-slug: sitecloudidconversationconversationidappmodulechatwebhookkey-put
      parameters:
      - in: path
        name: cloudId
        description: The id of the site (cloudId)
      - in: path
        name: conversationId
        description: The conversation id
      - in: path
        name: key
        description: The key to identify the resource
      responses:
        200:
          description: OK
      tags:
      - Update
      - Chat:webhook
      - Module
---