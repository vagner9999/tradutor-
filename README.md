# tradutor-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>HTML</title>
  
  <!-- HTML -->
</head>
<body>
  <p><strong>QUERY LENGTH LIMIT EXCEEDED. MAX ALLOWED QUERY : 500 CHARS.</p>
  <!-- Project -->
</body>
</html>
  <style>
    .flags {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
    }

    .flag {
      margin: 20px;
      border: 1px solid black;
      box-shadow: 5px 5px 10px gray;
    }

    img {
      width: 300px;
      height: 200px;
    }strong{color:White;}
  </style>
</head>
<body>
  
    <div class="flag">
      <img src=" https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_LI1XxjAnq0KKrJZ--K19qX63gM9O7Xx3wg&usqp=CAU" alt="Bandeira da França">
    
  </section>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Language Translator | Coding</title>
  <link rel="stylesheet" href="style.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
</head>

<body>
  <div class="container">
    <h1 class="f">translator</h1></strong>
    <div class="wrapper">
      <div class="text-input">
        <textarea spellcheck="false" class="from-text" placeholder="Enter text"></textarea>
        <textarea spellcheck="false" readonly disabled class="to-text" placeholder="Translation"></textarea>
      </div>
      <ul class="controls">
        <li class="row from">
          <div class="icons">
            <i id="from" class="fas fa-volume-up"></i></div><div>
            <i id="from" class="fas fa-copy"></i>
          </div><div>
          <select></select>
        </li>
        <li class="exchange"><i class="fas fa-exchange-alt"></i></li></div><div>
        <li class="row to">
          <select></select>
          <div class="icons"></div><div>
            <i id="to" class="fas fa-copy"></i>
          </div>
        </li>
      </ul>
    </div>
    <button>Translate Text</button>
  </div><div>
    <button id="clear-button">clear text </button>
  </div><div></div>

<style>/* Import Google Font - Poppins */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}



.container {
  max-width: 690px;
  width: 100%;
  padding: 30px;
  background: #fff;
  border-radius: 7px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.01);
}

.wrapper {
  border-radius: 5px;
  border: 1px solid #ccc;
}

.wrapper .text-input {
  display: flex;
  border-bottom: 1px solid #ccc;
}

.text-input .to-text {
  border-radius: 0px;
  border-left: 1px solid #ccc;
}

.text-input textarea {
  height: 250px;
  width: 100%;
  border: none;
  outline: none;
  resize: none;
  background: none;
  font-size: 18px;
  padding: 10px 15px;
  border-radius: 5px;
}

.text-input textarea::placeholder {
  color: #b7b6b6;
}

.controls,
li,
.icons,
.icons i {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.controls {
  list-style: none;
  padding: 12px 15px;
}

.controls .row .icons {
  width: 38%;
}

.controls .row .icons i {
  width: 50px;
  color: #adadad;
  font-size: 14px;
  cursor: pointer;
  transition: transform 0.2s ease;
  justify-content: center;
}

.controls .row.from .icons {
  padding-right: 15px;
  border-right: 1px solid #ccc;
}

.controls .row.to .icons {
  padding-left: 15px;
  border-left: 1px solid #ccc;
}

.controls .row select {
  color: #333;
  border: none;
  outline: none;
  font-size: 18px;
  background: none;
  padding-left: 5px;
}

.text-input textarea::-webkit-scrollbar {
  width: 4px;
}

.controls .row select::-webkit-scrollbar {
  width: 8px;
}

.text-input textarea::-webkit-scrollbar-track,
.controls .row select::-webkit-scrollbar-track {
  background: #fff;
}

.text-input textarea::-webkit-scrollbar-thumb {
  background: #ddd;
  border-radius: 8px;
}

.controls .row select::-webkit-scrollbar-thumb {
  background: #999;
  border-radius: 8px;
  border-right: 2px solid #ffffff;
}

.controls .exchange {
  color: #adadad;
  cursor: pointer;
  font-size: 16px;
  transition: transform 0.2s ease;
}

.controls i:active {
  transform: scale(0.9);
}

.container button {
  width: 100%;
  padding: 14px;
  outline: none;
  border: none;
  color: #fff;
  cursor: pointer;
  margin-top: 20px;
  font-size: 17px;
  border-radius: 5px;
  background: #5372F0;
}

@media (max-width: 660px) {
  .container {
    padding: 20px;
  }

  .wrapper .text-input {
    flex-direction: column;
  }

  .text-input .to-text {
    border-left: 0px;
    border-top: 1px solid #ccc;
  }

  .text-input textarea {
    height: 300px;
  }

  .controls .row .icons {
    display: none;
  }

  .container button {
    padding: 13px;
    font-size: 16px;
  }

  .controls .row select {
    font-size: 16px;
  }

  .controls .exchange {
    font-size: 14px;
  }
}

.f {
  text-align: center;
  color:White;
  border-color:navy;
  border-style: solid black;
}

.f:hover {
  text-align: left;
  color: white;
  border-color: none;
  border-style: solid;
  background-color:navy;
}</style>
  <script src="countries.js"></script>
  <script src="script.js"></script>
<script>const countries = {
  "pt-BR": "Portugues",
  "am-ET": "Amharic",
  "ar-SA": "Arabic",
  "be-BY": "Bielarus",
  "bem-ZM": "Bemba",
  "bi-VU": "Bislama",
  "bjs-BB": "Bajan",
  "bn-IN": "Bengali",
  "bo-CN": "Tibetan",
  "br-FR": "Breton",
  "bs-BA": "Bosnian",
  "ca-ES": "Catalan",
  "cop-EG": "Coptic",
  "cs-CZ": "Czech",
  "cy-GB": "Welsh",
  "da-DK": "Danish",
  "dz-BT": "Dzongkha",
  "de-DE": "German",
  "dv-MV": "Maldivian",
  "el-GR": "Greek",
  "en-GB": "English",
  "es-ES": "Spanish",
  "et-EE": "Estonian",
  "eu-ES": "Basque",
  "fa-IR": "Persian",
  "fi-FI": "Finnish",
  "fn-FNG": "Fanagalo",
  "fo-FO": "Faroese",
  "fr-FR": "French",
  "gl-ES": "Galician",
  "gu-IN": "Gujarati",
  "ha-NE": "Hausa",
  "he-IL": "Hebrew",
  "hi-IN": "Hindi",
  "hr-HR": "Croatian",
  "hu-HU": "Hungarian",
  "id-ID": "Indonesian",
  "is-IS": "Icelandic",
  "it-IT": "Italian",
  "ja-JP": "Japanese",
  "kk-KZ": "Kazakh",
  "km-KM": "Khmer",
  "kn-IN": "Kannada",
  "ko-KR": "Korean",
  "ku-TR": "Kurdish",
  "ky-KG": "Kyrgyz",
  "la-VA": "Latin",
  "lo-LA": "Lao",
  "lv-LV": "Latvian",
  "men-SL": "Mende",
  "mg-MG": "Malagasy",
  "mi-NZ": "Maori",
  "ms-MY": "Malay",
  "mt-MT": "Maltese",
  "my-MM": "Burmese",
  "ne-NP": "Nepali",
  "niu-NU": "Niuean",
  "nl-NL": "Dutch",
  "no-NO": "Norwegian",
  "ny-MW": "Nyanja",
  "ur-PK": "Pakistani",
  "pau-PW": "Palauan",
  "pa-IN": "Panjabi",
  "ps-PK": "Pashto",
  "pis-SB": "Pijin",
  "pl-PL": "Polish",
  "pt-PT": "Portuguese",
  "rn-BI": "Kirundi",
  "ro-RO": "Romanian",
  "ru-RU": "Russian",
  "sg-CF": "Sango",
  "si-LK": "Sinhala",
  "sk-SK": "Slovak",
  "sm-WS": "Samoan",
  "sn-ZW": "Shona",
  "so-SO": "Somali",
  "sq-AL": "Albanian",
  "sr-RS": "Serbian",
  "sv-SE": "Swedish",
  "sw-SZ": "Swahili",
  "ta-LK": "Tamil",
  "te-IN": "Telugu",
  "tet-TL": "Tetum",
  "tg-TJ": "Tajik",
  "th-TH": "Thai",
  "ti-TI": "Tigrinya",
  "tk-TM": "Turkmen",
  "tl-PH": "Tagalog",
  "tn-BW": "Tswana",
  "to-TO": "Tongan",
  "tr-TR": "Turkish",
  "uk-UA": "Ukrainian",
  "uz-UZ": "Uzbek",
  "vi-VN": "Vietnamese",
  "wo-SN": "Wolof",
  "xh-ZA": "Xhosa",
  "yi-YD": "Yiddish",
  "zu-ZA": "Zulu"
};const fromText = document.querySelector(".from-text"),
  toText = document.querySelector(".to-text"),
  exchageIcon = document.querySelector(".exchange"),
  selectTag = document.querySelectorAll("select"),
  icons = document.querySelectorAll(".row i");
translateBtn = document.querySelector("button"),

  selectTag.forEach((tag, id) => {
    for (let country_code in countries) {
      let selected = id == 0 ? country_code == "pt-BR" ? "selected" : "" : country_code == "en-GB" ? "selected" : "";
      let option = `<option ${selected} value="${country_code}">${countries[country_code]}</option>`;
      tag.insertAdjacentHTML("beforeend", option);
    }
  });var text = "Hello";
var languages = ["es", "fr", "de", "pt", "ru"];

languages.forEach(function(language) {
  var translatedText = translate(text, "en", language);
  console.log("Texto traduzido para " + language + ": " + translatedText);
});

function translate(text, fromLang, toLang) {
  // Aqui você pode usar uma API de tradução, como o Google Translate API,
  // para fazer a tradução do texto.
  // Por simplicidade, neste exemplo usamos uma função que retorna apenas
  // o texto traduzido para vários idiomas.
  switch (toLang) {
    case "es":
      return "Hola";
    case "fr":
      return "Bonjour";
    case "de":
      return "Hallo";
    case "pt":
      return "Olá";
    case "ru":
      return "Здравствуйте";
    default:
      return text;
  }
};


exchageIcon.addEventListener("click", () => {
  let tempText = fromText.value,
    tempLang = selectTag[0].value;
  fromText.value = toText.value;
  toText.value = tempText;
  selectTag[0].value = selectTag[1].value;
  selectTag[1].value = tempLang;
});

fromText.addEventListener("keyup", () => {
  if (!fromText.value) {
    toText.value = "";
  }
});

translateBtn.addEventListener("click", () => {
  let text = fromText.value.trim(),
    translateFrom = selectTag[0].value,
    translateTo = selectTag[1].value;
  if (!text) return;
  toText.setAttribute("placeholder", "Translating...");
  let apiUrl = `https://api.mymemory.translated.net/get?q=${text}&langpair=${translateFrom}|${translateTo}`;
  fetch(apiUrl).then(res => res.json()).then(data => {
    toText.value = data.responseData.translatedText;
    data.matches.forEach(data => {
      if (data.id === 0) {
        toText.value = data.translation;
      }
    });
    toText.setAttribute("placeholder", "Translation");
  });
});

icons.forEach(icon => {
  icon.addEventListener("click", ({ target }) => {
    if (!fromText.value || !toText.value) return;
    if (target.classList.contains("fa-copy")) {
      if (target.id == "from") {
        navigator.clipboard.writeText(fromText.value);
      } else {
        navigator.clipboard.writeText(toText.value);
      }
    } else {
      let utterance;
      if (target.id == "from") {
        utterance = new SpeechSynthesisUtterance(fromText.value);
        utterance.lang = selectTag[0].value;
      } else {
        utterance = new SpeechSynthesisUtterance(toText.value);
        utterance.lang = selectTag[1].value;
      }
      speechSynthesis.speak(utterance);
    }
  });
});</script>

<div class="wrapper">
  <div class="text-input">
    <textarea spellcheck></textarea>
  </div>


<style>
  .wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  #clear-button {
    width: 150px;
    height: 70px;
    margin-top: 120px;
    background-color:#20a;
    border: none;
    border-radius: 5px;
    color: white;
    font-size: 16px;
    cursor: pointer;
  }
</style>

<script>
  const clearButton = document.querySelector("#clear-button");
  const textInput = document.querySelector(".text-input textarea");

  clearButton.addEventListener("click", function() {
    textInput.value = "";
  });
</script>
</div><div><strong>Coding By vagner pires  &#174 reserved .</strong></div>
<style>

body { background-image: url("https://i.redd.it/eyohsf22z2551.jpg"); background-color: #cccccc; width: 100%; height: auto; } .converter { background: rgb(5, 109, } #valorMoedaUm { font-family: 'Secular One'; width: 13.4rem; color: rgb(35, 35, 35); padding: 0.75rem; margin: 0.05rem 1.25rem 1.75rem 0; border-radius: 20px; } #valorMoedaDois { background-color: white; font-family: 'Secular One'; width: 13.4rem; padding: 0.75rem; margin: 0.05rem 1.25rem 1.75rem 0; border-radius: 20px; } #valorMoedaUm::-webkit-inner-spin-button { -webkit-appearance: none; } button { font-family: 'Press Start 2P', cursive; text-shadow: 2px 2px #ff0000; width: 100%; color: rgb(30, 30, 30); background: rgb(254, 225, 112); font-size:4rem; padding: 1.25;  margin: 1.5rem 0 0 0; transition: 200ms; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; } button:hover { background: rgb(153, 255, 153); }</style>
