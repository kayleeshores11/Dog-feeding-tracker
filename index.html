<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="theme-color" content="#f4efe8" />
  <title>Charlie & Marlee Feeding Tracker</title>
  <style>
    :root {
      --bg: #f4efe8;
      --card: #fffdf9;
      --text: #2f2b27;
      --muted: #766f67;
      --accent: #5d7a68;
      --accent-dark: #486153;
      --border: #e4ddd4;
      --soft: #f8f4ef;
      --shadow: 0 12px 30px rgba(62, 49, 38, 0.10);
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      display: flex;
      justify-content: center;
      align-items: flex-start;
      padding: 22px;
    }

    .app {
      width: min(100%, 440px);
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 24px;
      box-shadow: var(--shadow);
      padding: 26px 20px 24px;
    }

    .dogs {
      font-size: 46px;
      text-align: center;
      margin-bottom: 6px;
    }

    h1 {
      margin: 0;
      text-align: center;
      font-size: 27px;
      letter-spacing: -0.5px;
    }

    .subtitle {
      margin: 8px 0 22px;
      text-align: center;
      color: var(--muted);
      font-size: 15px;
    }

    .meal {
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 18px;
      margin-bottom: 16px;
      background: #fff;
    }

    .meal-title {
      font-size: 20px;
      font-weight: 800;
      margin-bottom: 10px;
    }

    .status {
      background: var(--soft);
      border-radius: 14px;
      padding: 13px 14px;
      margin-bottom: 12px;
    }

    .label {
      color: var(--muted);
      font-size: 12px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 5px;
    }

    .last-fed {
      font-size: 17px;
      font-weight: 700;
      line-height: 1.3;
    }

    .fed-by {
      color: var(--muted);
      margin-top: 3px;
      font-size: 14px;
    }

    .person-buttons {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
    }

    button {
      border: 0;
      border-radius: 14px;
      padding: 14px 10px;
      font-size: 15px;
      font-weight: 700;
      cursor: pointer;
      transition: transform .08s ease, background .15s ease;
    }

    button:active { transform: scale(0.98); }

    .person {
      background: var(--accent);
      color: white;
    }

    .person:hover { background: var(--accent-dark); }

    .notify {
      width: 100%;
      margin: 2px 0 14px;
      background: #fff;
      color: var(--text);
      border: 1px solid var(--border);
    }

    .reset {
      width: 100%;
      margin-top: 4px;
      background: transparent;
      color: var(--muted);
      border: 1px solid var(--border);
      font-weight: 600;
      font-size: 14px;
      padding: 11px;
    }

    .note {
      color: var(--muted);
      font-size: 12px;
      line-height: 1.5;
      text-align: center;
      margin: 14px 8px 0;
    }

    .toast {
      display: none;
      margin: 10px 0 14px;
      padding: 11px;
      border-radius: 13px;
      background: #e9f0eb;
      color: #355243;
      text-align: center;
      font-weight: 650;
      font-size: 14px;
    }

    .toast.show { display: block; }
  </style>
</head>
<body>
  <main class="app">
    <section class="card">
      <div class="dogs">🐶🐶</div>
      <h1>Charlie & Marlee</h1>
      <p class="subtitle">Feeding tracker for Kaylee & Kate</p>

      <button class="notify" onclick="enableNotifications()">
        🔔 Enable notifications
      </button>

      <div class="toast" id="toast"></div>

      <section class="meal">
        <div class="meal-title">🌅 Breakfast</div>

        <div class="status">
          <div class="label">Last breakfast</div>
          <div class="last-fed" id="breakfastTime">No breakfast logged yet</div>
          <div class="fed-by" id="breakfastBy"></div>
        </div>

        <div class="person-buttons">
          <button class="person" onclick="logFeeding('breakfast', 'Kaylee')">Kaylee fed them</button>
          <button class="person" onclick="logFeeding('breakfast', 'Kate')">Kate fed them</button>
        </div>
      </section>

      <section class="meal">
        <div class="meal-title">🌙 Dinner</div>

        <div class="status">
          <div class="label">Last dinner</div>
          <div class="last-fed" id="dinnerTime">No dinner logged yet</div>
          <div class="fed-by" id="dinnerBy"></div>
        </div>

        <div class="person-buttons">
          <button class="person" onclick="logFeeding('dinner', 'Kaylee')">Kaylee fed them</button>
          <button class="person" onclick="logFeeding('dinner', 'Kate')">Kate fed them</button>
        </div>
      </section>


      <section class="meal">
        <div class="meal-title">💧 Water Bowl</div>

        <div class="status">
          <div class="label">Last cleaned</div>
          <div class="last-fed" id="waterTime">No cleaning logged yet</div>
          <div class="fed-by" id="waterBy"></div>
        </div>

        <div class="person-buttons">
          <button class="person" onclick="logFeeding('water', 'Kaylee')">Kaylee cleaned it</button>
          <button class="person" onclick="logFeeding('water', 'Kate')">Kate cleaned it</button>
        </div>
      </section>

      <p class="note">
        Breakfast, dinner, and water-bowl cleaning are synced through the shared Google Sheet. The page
        refreshes shared status automatically while open. Browser notifications
        currently confirm feeding on the device that logs it; cross-device push
        alerts will be added separately.
      </p>
    </section>
  </main>

  <script>
    const API_URL = "https://script.google.com/macros/s/AKfycbwKFTvS-ttv4_kFki1GJmuyP4qbdaU5k-r_9CNoHZbRWb8w09qzrYk68kVu-9a_ucjfDQ/exec";

    function formatDateTime(dateString) {
      const d = new Date(dateString);
      return d.toLocaleString([], {
        weekday: "short",
        month: "short",
        day: "numeric",
        hour: "numeric",
        minute: "2-digit"
      });
    }

    function renderMeal(meal, entry) {
      const timeEl = document.getElementById(meal + "Time");
      const byEl = document.getElementById(meal + "By");

      if (!entry) {
        if (meal === "breakfast") {
          timeEl.textContent = "No breakfast logged yet";
        } else if (meal === "dinner") {
          timeEl.textContent = "No dinner logged yet";
        } else {
          timeEl.textContent = "No cleaning logged yet";
        }
        byEl.textContent = "";
        return;
      }

      timeEl.textContent = formatDateTime(entry.time);
      byEl.textContent = "Fed by " + entry.person;
    }

    function showToast(message) {
      const toast = document.getElementById("toast");
      toast.textContent = message;
      toast.classList.add("show");
      setTimeout(() => toast.classList.remove("show"), 2400);
    }

    function jsonpRequest(params) {
      return new Promise((resolve, reject) => {
        const callbackName =
          "dogTrackerCallback_" + Date.now() + "_" + Math.floor(Math.random() * 100000);

        const script = document.createElement("script");
        const query = new URLSearchParams({
          ...params,
          callback: callbackName
        });

        const timeout = setTimeout(() => {
          cleanup();
          reject(new Error("Request timed out"));
        }, 10000);

        function cleanup() {
          clearTimeout(timeout);
          delete window[callbackName];
          if (script.parentNode) script.parentNode.removeChild(script);
        }

        window[callbackName] = (data) => {
          cleanup();
          resolve(data);
        };

        script.onerror = () => {
          cleanup();
          reject(new Error("Could not reach feeding tracker backend"));
        };

        script.src = API_URL + "?" + query.toString();
        document.body.appendChild(script);
      });
    }

    async function loadStatus() {
      try {
        const data = await jsonpRequest({ action: "status" });

        if (!data.success) {
          throw new Error(data.error || "Unable to load status");
        }

        renderMeal("breakfast", data.breakfast);
        renderMeal("dinner", data.dinner);
        renderMeal("water", data.water);
      } catch (error) {
        console.error(error);
        showToast("Could not load shared feeding status.");
      }
    }

    async function logFeeding(meal, person) {
      const mealName = meal === "water"
        ? "Water bowl cleaning"
        : meal.charAt(0).toUpperCase() + meal.slice(1);
      showToast(`Logging ${mealName.toLowerCase()}...`);

      try {
        const result = await jsonpRequest({
          action: "feed",
          meal: meal,
          person: person
        });

        if (!result.success) {
          throw new Error(result.error || "Unable to log feeding");
        }

        showToast(`✓ ${mealName} logged by ${person}`);
        sendNotification(meal, person);
        await loadStatus();
      } catch (error) {
        console.error(error);
        showToast("Feeding was not saved. Check the connection.");
      }
    }

    async function enableNotifications() {
      if (!("Notification" in window)) {
        showToast("Notifications are not supported in this browser.");
        return;
      }

      const permission = await Notification.requestPermission();

      if (permission === "granted") {
        showToast("Notifications enabled on this device.");
        new Notification("Charlie & Marlee", {
          body: "Feeding notifications are enabled on this device."
        });
      } else {
        showToast("Notification permission was not granted.");
      }
    }

    function sendNotification(meal, person) {
      if (!("Notification" in window)) return;
      if (Notification.permission !== "granted") return;

      const mealName = meal === "water"
        ? "Water bowl cleaning"
        : meal.charAt(0).toUpperCase() + meal.slice(1);

      new Notification(
        meal === "water" ? "Charlie & Marlee's water bowl was cleaned 💧" : "Charlie & Marlee have been fed 🐶",
        {
          body: `${mealName} was logged by ${person}.`
        }
      );
    }

    loadStatus();
    setInterval(loadStatus, 30000);
  </script>
</body>
</html>
