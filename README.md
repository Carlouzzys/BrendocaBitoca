    <script>
        function calcularDias() {
            const dataInicio = new Date(2023, 8, 18); // 18 de setembro de 2023
            const hoje = new Date();
            const diferenca = Math.floor((hoje - dataInicio) / (1000 * 60 * 60 * 24));
            document.getElementById('days-counter').innerText = diferenca;
        }
        calcularDias();
    </script>
</body>
</html>
