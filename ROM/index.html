<script>
const pools = [
    "CPU/cpu.raw",
    "GPU/raw.raw",
    "RAM/ram.raw",
    "ROM/rom.raw",
    "POS/pos.raw",
    "FUSION/fus.raw",
    "TECH/raw.raw",
    "HOME/home.raw",
    "BODY/body.raw",
    "SCRIPT/scr.raw",
    "RAW6D/6d1d.r6d",
    "RAW6D/6d3.r6d",
    "RAW6D/test.r6d"
];

async function loadAllPools() {
    let results = [];

    for (const file of pools) {
        try {
            const response = await fetch(file);
            const buffer = await response.arrayBuffer();
            const bytes = new Uint8Array(buffer);

            // Schatten extrahieren
            const shadow = extractShadow(bytes);

            // Geometrie erzeugen
            const body = buildGeometry(bytes);

            results.push({
                file: file,
                size: bytes.length + " bytes",
                shadow: shadow,
                body: body
            });

        } catch (e) {
            results.push({
                file: file,
                error: "Konnte Datei nicht laden"
            });
        }
    }

    document.getElementById("geo-output").textContent =
        JSON.stringify(results, null, 2);
}

loadAllPools();
</script>
