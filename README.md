# SSH-

####################################
alias pvpn='mixtific$rcI5c'
alias pmiztli='Albr@so7!_BraS0'

alias vepene='sudo openvpn --config client.ovpn'
alias sshmiztli='sshpass -p Albr@so7!_BraS0 ssh abs_a@132.247.177.99'
alias sshocelote='sshpass -p termolab ssh ocelote@148.213.104.137'
alias sshsuricata='sshpass -p termolab ssh suricata@148.213.104.135'
alias sshtejon='sshpass -p termolab ssh tejon@148.213.104.134'
alias sshlince='sshpass -p termolab ssh lince@148.213.104.133'
alias sshmapachito='sshpass -p termolab ssh mapachito@148.213.104.138'
alias sshcocodrilo='sshpass -p termolab ssh cocodrilo@148.213.104.141'

alias sftpmiztli='sshpass -p Albr@so7!_BraS0 sftp abs_a@132.247.177.99'
alias sftpocelote='sshpass -p termolab sftp ocelote@148.213.104.137'
alias sftpsuricata='sshpass -p termolab sftp suricata@148.213.104.135'
alias sftptejon='sshpass -p termolab sftp tejon@148.213.104.134'
alias sftplince='sshpass -p termolab sftp lince@148.213.104.133'
alias sftpmapachito='sshpass -p termolab sftp mapachito@148.213.104.138'
alias sftpcocodrilo='sshpass -p termolab sftp cocodrilo@148.213.104.141'
#####################################


scp -P 3030 -r /home/suricata/Documents/potenciaHDZVIEJO abs_a@132.248.202.199:/LANCAD/home/naude_g/abs_a
rsync -avx -e "ssh -p 3030" --progress abs_a@132.248.202.199:/LANCAD/home/naude_g/abs_a/aneurysms/esparza/esparzaNewto .

OSIDIFF
Append attribute
100*((abs((OSI_input_1)-(OSI)))/(OSI_input_1))
o
python calculator
100*(abs(inputs[1].PointData['OSI'] - inputs[0].PointData['OSI']))/(inputs[1].PointData['OSI'])

