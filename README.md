# HATTICIZER PROTOCOL v4.5

> A Context-Free, Agglutinative Structural Matrix Shifter for the Pre-Greek Aegean

The Hatticizer Protocol v4.5 is a specialized historical-linguistic computation engine designed to isolate, map, and compile the non-Indo-European (non-IE) Aegean substrate (including the Eteocretan, Linear A, and Anatolian Hattic layers). This framework treats prehistoric toponyms, ritual formulas, and administrative registries as functional string tokens to model Bronze Age palatial redistribution networks.

---

## 🛠️ System Architecture

The core runtime evaluates text strings using a position-dependent, left-to-right **6-Slot Agglutination Pipeline**. 

```text
[ S0: Directive ] ──► [ S1: Metric ] ──► [ S2: Focus ] ──► [ S3: Redup ] ──► [ S4: Core ] ──► [ S5: Closer ]
```

### Slot Definitions & Matrix Components

*   **Slot 0 (S0) — Architectural Vectors & Directives:** Maps outbound execution commands and border boundary gates (e.g., `U` 𐘉, `ZA` 𐘴, `DA` 𐘿, `AN` 𐘀𐘴).
*   **Slot 1 (S1) — Locative, Collective, and Storage Metrics:** Sets institutional class monopoly flags, vault locks, and volumetric capacities (e.g., `A` 𐘀, `TE` 𐘃, `SI` 𐘈, `PU` 𐘅, `ME` 𐘯).
*   **Slot 2 (S2) — Deictic Focus & Domain Specifiers:** Establishes sovereign palatial command stamps, decrees, and fortified cliff repository focuses (e.g., `JA` 𐘌, `RA` 𐘤, `RE` 𐘕, `RI` 𐘚).
*   **Slot 3 (S3) — "Double-Tap" Reduplication:** An automated checking daemon that catches adjacent, duplicate tokens (e.g., `TA-TA`, `RE-RE`), tracking legal or metric property duplication metrics.
*   **Slot 4 (S4) — Immutable Core Argument:** Processed as an un-inflected baseline token placeholder (`[𐘝]`). It acts as the foundational root anchoring the prefixes.
*   **Slot 5 (S5) — Master Morphosyntactic Enclitic Closers:** Clamps the data block shut using validated word-boundary suffixes (e.g., `-JA` 𐘌, `-NE` 𐘗, `-TA` 𐘳, `-ME` 𐘯). Optimized to comply with the long-form Linear A discoveries published in the *Ariadne 2026* tape supplement.

---

### 🏛️ Division of Labor & Operational Modes

The engine dynamically determines the structural division of labor by evaluating the categorization of the **Slot 5 Enclitic Closer**. Depending on the target suffix, the system automatically routes the token sequence into one of two operational states:

#### 1. Static Containment (Desk Accounting)
Triggered when the matrix is clamped shut by a preservation, locking, or institutional boundary marker. This mode establishes that the ledger asset is fixed within a physical palatial archive or static storage compound.
*   **Active Suffixes:** `-JA`, `-NE`, `-TA`, `-TO`, `-ME`
*   **System Logic:**
    ```python
    is_static = target_closer.upper() in ["-JA", "-NE", "-TA", "-TO", "-ME"]
    # Sets division_of_labor to: "STATIC CONTAINMENT (DESK ACCOUNTING)"
    ```

#### 2. Kinetic Projection (Mobile Pipeline)
Triggered when the matrix uses an operational suffix that dictates motion, outward tasks, or fluid volumetric scaling. This mode indicates that the assets are actively moving through supply lines, international shipping pipelines, or outbound distribution tracks.
*   **Active Suffixes:** `-U`, `-MA`
*   **System Logic:** 
    ```python
    # If not static, sets division_of_labor to: "KINETIC PROJECTION (MOBILE PIPELINE)"
    ```

---

## 🔍 Error Handling, Diagnostics & Fallback Protocols

The Hatticizer engine is built with a deterministic validation matrix. Because it parses text strings using fixed dictionaries, any sequence component that does not precisely match an established key in Slots 0, 1, or 2 triggers an intentional fallback protocol.

#### 1. Prehistoric Root Isolation (`[𐘝]`)
When the parser encounters a raw, un-inflected, or unrecognized substring, it does not throw an unhandled exception or corrupt the pipeline. Instead, it treats the token as an underlying lexical root anchor.
* **System Action:** The unrecognized token is mapped directly to the **Slot 4 (S4) Baseline Placeholder**: `[𐘝]`.
* **Diagnostic Logging:** The internal execution pass explicitly registers the event to track raw substrate variants:
  ```text
  [ROOT Core]    Processed un-inflected baseline token: [your_token]
  ```

#### 2. Unknown S5 Ledger Closers (`[?]`)
If an invalid or untracked enclitic suffix is passed to the runtime environment as a target closer, the system applies a generic boundary block to prevent data leakage.
* **System Action:** Maps the closing sign to an unknown status symbol `[?]` and marks its function description as `"Unknown Closer"`.
* **System Impact:** The engine will still process the string, but the `division_of_labor` will automatically route to **KINETIC PROJECTION (MOBILE PIPELINE)** because it fails the explicit static boundary list verification check.

#### Diagnostic Log Sample Output
When passing an un-inflected root sequence (e.g., `A-RE-NE-SI-DI-JE`) into the validation gates, the `logs` array provides absolute visibility into how the matrix resolves the string:

```text
[S1 Metric]    Mapped prefix A   -> Macro-Collective Intensive State Canopy Modifier
[ROOT Core]    Processed un-inflected baseline token: RE
[ROOT Core]    Processed un-inflected baseline token: NE
[S1 Metric]    Mapped prefix SI  -> Vault-Lock / High-Security Subterranean Isolation Custody
[ROOT Core]    Processed un-inflected baseline token: DI
[ROOT Core]    Processed un-inflected baseline token: JE
[S5 Closer]    Matrix clamped shut via -TA -> Anetaki Scepter Update / Definitive Closed Ledger Suffix
```

---

## 🌾 Commodity Bank & Volumetric Constants

The engine translates raw volume values directly into standard Minoan numeric tally markings (`𐚾` for Tens, `𐚽` for Ones, `𐚼` for Zero) and cross-references volumetric counts against fixed caloric energetic constraints:

| Commodity | Ideogram | Catalog ID | Calories / Unit | Function |
| :--- | :---: | :---: | :---: | :--- |
| **Grain** | 𐚡 | AB120 | 360,000 | Bulk dry rations |
| **Oil** | 𐚣 | AB122 | 820,000 | Liquid fluid bank |
| **Wine** | 𐚦 | AB131 | 240,000 | Luxury ration unit |
| **Cloth** | 𐘸 | B159 | 500,000 | Textile currency cloth |

---

## 💻 Script API Usage

### 1. Basic Infrastructure Verification Pass

```python
from hatticizer_mainframe import HatticizerMainframeV45

# Initialize v4.5 engine pipeline
mainframe = HatticizerMainframeV45()

# Parse a sequence string through the infrastructure validation gates
result = mainframe.execute_infrastructure_parse(
    profile_name="Mavro_Spilio_Core",
    sequence_string="A-RE-NE-SI-DI-JE",
    target_closer="-TA"
)

print(result["visual_chain"])       # Output: Agglutinated character string
print(result["division_of_labor"])  # Output: STATIC CONTAINMENT (DESK ACCOUNTING)
```

### 2. Caloric Redistribution & Inscribed Tally Stamping

To log an authoritative ledger entry with tally marks and compute thermodynamic distribution weights, call the redistribution module:

```python
# Process a 25-unit dry ration allocation
tally_entry = mainframe.process_caloric_redistribution(
    parse_result=result,
    commodity_type="grain",
    volume_units=25,
    mycenaean_genitive=False
)

print(tally_entry)
# Output: [Visual Chain String] ──► 𐚡 (𐚾𐚾𐚽𐚽𐚽𐚽𐚽) | Modulus Balance: 9,000,000 Total Calories
```

*Note: Pass `mycenaean_genitive=True` to explicitly inject the intrusive Linear B `JO` sign (`𐘏`) override into the chain.*

---# hatticizer_v4_5



