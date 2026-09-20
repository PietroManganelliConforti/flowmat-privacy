# L'informativa privacy di FlowMat

Una pagina sola, pubblicata con GitHub Pages, perché Google Play vuole un **indirizzo
pubblico** dell'informativa prima di accettare qualunque pubblicazione. Il gioco sta in un
altro repo, che resta privato: qui c'è soltanto la pagina che chiunque deve poter leggere.

    https://pietromanganelliconforti.github.io/flowmat-privacy/

`index.html` e `privacy.html` sono lo stesso file, così funzionano tutti e due gli
indirizzi — quello corto e quello con il nome, che è quello già scritto nei documenti.

## Quando l'informativa cambia

**Non si modifica qui.** L'originale vive nel repo del gioco, in `public/privacy.html`: è
quello che finisce dentro l'app e che «Info e legale» mostra anche senza connessione. Di
lì si ricopia:

    cp ../nogi-simulator/public/privacy.html privacy.html
    cp privacy.html index.html
    git commit -am "l'informativa aggiornata" && git push

Tenerle allineate non è un vezzo: un'informativa diversa dentro l'app e sul web è
esattamente la cosa che Play e il GDPR chiedono di non fare.
