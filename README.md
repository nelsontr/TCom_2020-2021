<a href="http://fenix.tecnico.ulisboa.pt"><img align="right" src="https://fenix.tecnico.ulisboa.pt/api/bennu-portal/configuration/logo" alt="Fenix Tecnico"></a>

# TCOM_20-21

Theory of Computation 2020/2021

#### Group nº11
- @biacalves
- @KasaiZERA
- @nelsontr

### Project

#### Topics
- [Código](complem.txt) | *MT* **Complementar**
- [Código](compor.txt) | *MT* **Função Composta**
- [Código](while.txt) | *MT* **While**
- [Código](ifthenelse.txt) | MT **IfThenElse**

### Grade
| Solution          | Grade 		  |
| :-----------------| :-----------------: |
| *MT* **Complementar** | *00.0* / 0.50 |
| *MT* **Função** | *00.0* / 1.00 |
|	*MT* **While**	| *00.0* / 1.00  |
|	*MT* **IfThenElse** | *00.0* / 1.50  |



# Notas Práticas

## complem.txt

* [x] Feito, falta dúvidas.

- Temos de verificar input?

- 1 fita (2 fitas?), onde a ultima output: onde está YY* meter NN* e vice versa

### FAQ

**Q: É preciso o cursor estar no inicio do output?**

**A:** O resultado deve ficar na ultima fita e o ponteiro deve ficar no inicio do resultado

---

**Q: É preciso verificar o input?**

**A:** Vão sempre ser apresentadas da forma correta.



## compor.txt

- ***M1$M2*** em que o **$** é só para diferenciar, mas tem de estar na maquina...
- Quando chegar o final:  colocar `;` em vez de **$**
- ver maior estado
- voltar ao inicio

### FAQ

**Q: How the hell `soma`??**

**A:** Não é necessário. Pode colocar um output com K=2 mesmo recebendo máquina só com K=1.

---

**Q: O seguinte é possivel?**

```
input = Q0A1Q0A1L;Q0A0YYA1S$Q0A1Q0A1L;Q0A0YYA1S
---
output = Q00A1Q00A1L;Q00A0Q10A1S;Q10A1Q10A1L;Q10A0YYYA1S
```

**A:** Sim, a sua solução está certíssimo para as máquinas dadas.


## while.txt

- modifica o c?
- **C==Y**: M
- **M==Y**: C
- **M==N**: rej

## ifthenelse.txt

- Compor + Maquina para o reject
