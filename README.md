# iptables
Iptables does help fo anonymity and stop backdoor

Use iptables-apply using the iptables rules
>iptables-apply iptables-rules-allow-only-https

To watch dropped packets run: 
>journalctl -k -f

I know that backdoor can bypass this rules using https port but at least you can know what is going with your machine through logs :-).


