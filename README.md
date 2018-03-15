# ansible-playbook-example
Contains playbook examples in YAML.<br>
Set up guide:
<i>Requires:<i>
  <ul>
    <li>Ansible</li>
    <li>EC-2 Server running</li>
  </ul>
 <p> Make sure to modify the <code>hosts</code> file in the directory <code>/etc/ansible/hosts</code> <br>
  using the following command <code>sudo gedit hosts.</code> <br>
  Also specify the following: <br>
  <code>
    [groupofservers]
    `ip address of your ec2 server` ansible_user=`your ennsible user id`
  </code>

