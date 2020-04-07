# advpl_react_controle_acessos_backend

<p>O ERP Protheus possui uma boa estrutura de controle de acessos e permiss�es, por�m nunca estamos satisfeitos e sempre queremos mais.</p>

<p>Pensando nesse cen�rio trarei uma sequ�ncia de postagens com o objetivo de construirmos juntos uma camada extra de controle de acessos �s rotinas padr�es, aplicando o conceito de backend utilizando o<strong> Advpl com REST </strong>e o frontend utilizando a biblioteca javascript <strong>ReactJS.</strong></p>

<h3>Objetivo</h3>

<p>Construir uma customiza��o no ERP Protheus que possibilite controlar o acesso de usu�rios nas rotinas padr�es, permitindo que esse controle seja realizado por rotina e para cada bot�o dispon�vel nessa rotina.</p>

<p>Toda manuten��o dessa processo ser� realizado atrav�s de interface web e integrada com o ERP Protheus atrav�s de<strong> API REST.</strong></p>

<p>O objetivo dessa ferramenta � did�tico, utilize por conta e risco.</p>

<h3>Funcionalidades</h3>

<ul><li>Permitir acesso nas rotinas configuradas para apenas usu�rios autorizados.</li><li>Controlar o acesso a n�vel de bot�es existentes na rotina.</li><li>Garantir que mesmo o usu�rio possuindo a rotina no menu, n�o poder� realizar a��es a menos que isso seja previamente autorizado.</li></ul>

<h3>Requisitos</h3>

<ul><li>Cria��o de tabela para controle das permiss�es</li><li>Utiliza��o de ponto de entrada para validar as permiss�es</li><li>Utiliza��o da SX5 para controle das rotinas a serem monitoradas</li><li>ReactJS</li></ul>
