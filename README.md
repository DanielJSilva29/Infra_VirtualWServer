
# 🏢 Windows Server Active Directory Lab

## 📖 Sobre o Projeto
Este projeto consiste na implementação de uma infraestrutura de rede corporativa simulada. O objetivo foi replicar um cenário real de TI, configurando desde a virtualização até a gestão de identidade e políticas de segurança.

O laboratório demonstra competências práticas em administração de sistemas Windows, redes e virtualização, focando nas melhores práticas da Microsoft.

---

## 🏗️ Arquitetura e Topologia

O ambiente foi isolado utilizando Switches Virtuais no Hyper-V para simular uma rede local privada (LAN) com acesso controlado à WAN.

* **Host:** Windows 10 Pro (Hyper-V ativado)
* **SV01 (Server):** Controlador de Domínio, DNS, DHCP.
* **PC01:** Windows 11 ingressado no domínio.
