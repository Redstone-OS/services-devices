# devices

Orquestrador de Hardware (Device Manager).

## O que ele deve ser?
O "chefe dos drivers". Ele descobre o que está conectado ao PC e decide qual driver carregar.

## O que precisa fazer?
- [ ] **Bus Scanning**: Varrer barramentos PCI, USB e tabelas ACPI.
- [ ] **Driver Loading**: Lançar processos de drivers baseados no VendorID/ProductID.
- [ ] **Gestão de Recursos**: Alocar portas IO e IRQs para cada driver sem conflitos.
- [ ] **Hotplug**: Detectar quando um dispositivo é inserido ou removido.
- [ ] **Monitoramento**: Reiniciar drivers que travarem.
