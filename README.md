# ANSIBLE - CONFIGURATION MANAGEMENT
<br>

## Introduction
<br>
<ul>
<li>Ansible is often described as a configuration management tool and is typically mentioned in the same breath as Puppet, Chef, and Salt.</li>
<li>Ansible exposes a domain-specific language (DSL) that you use to describe the state of your servers.</li>
<li>You can use these tools for deployment as well.</li>
</ul>
<br>

## Push Based
<br>
<p>Ansible is push-based by default. Making a change looks like this:</p>
<br>
<ul>
<li>You: make a change to a playbook.</li>
<li>You: run the new playbook.</li>
<li>Ansible: connects to servers and executes modules, which changes server state.</li>
<li>As soon as you run the ansible-playbook command, Ansible connects to the remote servers and does its thing.</li>
</ul>