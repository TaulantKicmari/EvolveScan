# Preview Snippets (abstrahiert)

Diese Snippets zeigen die Struktur des Systems ohne echte Implementierung.

---

## FeatureExtractor (Preview)

```python
class FeatureExtractor:
    def extract(self, source_code):
        """Extrahiert strukturelle Merkmale."""
        pass
class MetaEngine:
    def evaluate(self, finding, features):
        """Aggregiert Scores und erzeugt Entscheidungen."""
        pass
class MiniAIPredictor:
    def predict(self, finding, features):
        """Erzeugt probabilistische Entscheidungen."""
        pass
---

## 📌 3. examples/sample_input.py

```bash id="x7m3qp"
mkdir -p examples

cat > examples/sample_input.py << 'EOF'
# Beispielinput für EvolveScan

def example(a, b):
    if a > b:
        return a - b
    return b - a
