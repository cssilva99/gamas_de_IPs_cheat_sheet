# IPv4

IPs Privados não são pagos na AWS



## Classe A
10.0.0.0 a 10.255.255.255

## Classe B
172.16.0.0 a 172.31.255.255

## Classe C
192.168.0.0 a 192.168.255.255


### Mascaras de Rede

## Classe A

## Classe B

255.255.0.0        /16
255.255.128.0      /17
255.255.192.0      /18
255.255.224.0      /19
255.255.240.0      /20
255.255.248.0      /21
255.255.252.0      /22
255.255.252.0      /23

## Classe C

255.255.255.0    /24


# IPv6

IPs Públicos são pagos na AWS a 0,005$
para forçar a transição para IPv6, onde os IPs são TODOS PÚBLICOS e todos GRATUITOS

# Roteamento

- Preencher uma Route Table da AWS é o mesmo que escrever uma Route Table numa rede on-premisses :

* roteamento estático

- A diferença está na camada de abstração :
  
* software vs. hardware

- Enquanto numa rede on-premises o next hop m é o endereço IP de uma interface física, como a GigabitEthernet0/1,

- na AWS o next hop (ou target), é uma abstração um recurso (ou serviço)

