<a href="http://fenix.tecnico.ulisboa.pt"><img align="right" src="https://fenix.tecnico.ulisboa.pt/api/bennu-portal/configuration/logo" alt="Fenix Tecnico"></a>

# TCOM_2020-2021

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
| *MT* **Complementar** | *0.50* / 0.50 |
| *MT* **Função** | *1.00* / 1.00 |
|	*MT* **While**	| *1.00* / 1.00  |
|	*MT* **IfThenElse** | *1.50* / 1.50  |



# Notas Práticas

<details>
<summary><b>Notas Práticas</b></summary>

## complem.txt

* [x] Feito.

- Temos de verificar input?

- 2 fitas, onde a ultima output: onde está YY* meter NN* e vice versa.

### FAQ

**Q: É preciso o cursor estar no inicio do output?**

**A:** O resultado deve ficar na ultima fita e o ponteiro deve ficar no inicio do resultado

---

**Q: É preciso verificar o input?**

**A:** Vão sempre ser apresentadas da forma correta.



## compor.txt

* [x] Feito.

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

* [x] Feito

- ***C$M1*** em que o **$** é só para diferenciar, mas tem de estar na maquina...

- modifica o c? (nope)

- **C==Y**: M_in
- **C==N**: acc
- **M==Y**: C_in
- **M==N**: rej

## ifthenelse.txt

* [x] Feito

- ***C$M1$M2*** em que o **$** é só para diferenciar, mas tem de estar na maquina...

- Mesma coisa que while, mas agora com uma 2ºmaquina para a rejeição da condição ***C***

</details>
