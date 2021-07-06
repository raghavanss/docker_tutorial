FROM ubuntu


RUN apt-get -y update
RUN apt -y git

RUN mkdir -p /opt/jenkins_agent
RUN mkdir -p /opt/jenkins_agent/agent_1_workspace

COPY agent.jar /opt/jenkins_agent

