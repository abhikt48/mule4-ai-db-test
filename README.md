# mule4-ai-db-test
Mule 4 test application with codeless agent, Mongo DB and MySql DB

# Steps for publish logs to APP Insight
1. Update connection [applicationinsights.json](https://github.com/abhikt48/mule4-ai-db-test/blob/main/agent/applicationinsights.json)
2. Dowload and copy `applicationinsights-agent-3.5.1.jar` in agent folder
3. Import application in Anypoint Studio
4. Run application with with VM argument `-javaagent:"***\agent\applicationinsights-agent-3.5.1.jar" `
