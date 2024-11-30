<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Code with GitHub Copilot

_GitHub Copilot, VS Code ve Codespaces içinde tamamlama tarzı öneriler sunarak kod yazmanıza yardımcı olabilir._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Copilot için VS Code ile Codespaces'ten faydalanın.

_"GitHub Copilot ve VS Code Kullanarak Yapay Zeka Destekli Kod Önerileriyle Geliştirme"ye Hoş Geldiniz! :wave:_

GitHub Copilot, kodu daha hızlı ve daha az çabayla yazmanıza yardımcı olan bir yapay zeka eş programcısıdır. Yorumlardan ve koddan bağlam alarak size anında tek satırlık kodlar veya tüm fonksiyonlar önerebilir. GitHub Copilot, OpenAI tarafından oluşturulan ve önceden eğitilmiş bir dil modeli olan OpenAI Codex tarafından desteklenmektedir.

**Copilot, VS Code, Visual Studio, JetBrains IDE ve Neovim gibi birçok kod editörüyle çalışır.**

Ayrıca, GitHub Copilot herkese açık depolarda bulunan tüm programlama dilleri üzerinde eğitilmiştir. Her dil için aldığınız önerilerin kalitesi, o dilin eğitim verisinin hacmi ve çeşitliliğine bağlı olarak değişebilir.  

Codespace içinde Copilot kullanmak, GitHub'ın [İş Birliğine Dayalı Kodlama](https://github.com/features#features-collaboration) araçlarıyla çalışmaya başlamanın ne kadar kolay olduğunu gösterir.

> **Not**
> Bu beceri alıştırması, GitHub Codespace'i kullanmaya odaklanacaktır. Bu alıştırmaya devam etmeden önce GitHub becerisi olan [Codespaces](https://github.com/skills/code-with-codespaces) rehberini tamamlamanız önerilir.

### :keyboard: Activity: Codespace içinde Copilot'u etkinleştir.

**Aşağıdaki etkinlikleri tamamlamak için bu talimatları referans olarak açık tutabilmek amacıyla başka bir tarayıcı sekmesi açmanızı öneririz.**

Bir repository üzerinde codespace açmadan önce, bir geliştirme konteyneri oluşturabilir ve codespace'inizde kullanılacak veya yüklenecek belirli uzantıları veya yapılandırmaları tanımlayabilirsiniz. Şimdi bu geliştirme konteynerini oluşturalım ve Copilot'u uzantılar listesine ekleyelim.

### Adım 1:
1. Repository'nizin **Code** sekmesine geri dönün, **Add file** açılır menüsüne tıklayın ve ardından `Create new file` seçeneğine tıklayın.
2. Boş metin alanına aşağıdaki kodu yazın veya yapıştırın:
   ```
   .devcontainer/devcontainer.json
   ```
3. Yeni **.devcontainer/devcontainer.json** dosyasının içine aşağıdaki içeriği ekleyin:
   ```
   {
       // Name this configuration
       "name": "Codespace for Skills!",
       "customizations": {
           "vscode": {
               "extensions": [
                   "GitHub.copilot"
               ]
           }
       }
   }
   ```
4. **Doğrudan `main` dalına commit yapma** seçeneğini seçin ve ardından **Yeni dosyayı commit et** butonuna tıklayın.  
5. Ekranın sol üst kısmındaki **Code** sekmesine tıklayarak repository'nizin ana sayfasına geri dönün.  
6. Sayfanın ortasında bulunan **Code** butonuna tıklayın.  
7. Açılan kutuda **Codespaces** sekmesine tıklayın.  
8. **Main üzerinde codespace oluştur** butonuna tıklayın.

   **Codespace'in açılması için yaklaşık 2 dakika bekleyin.**

9. Codespace'inizin çalıştığını doğrulayın. Tarayıcıda bir VS Code web tabanlı editörü ve aşağıdaki gibi bir terminal görünmelidir.
   ![Screen Shot 2023-03-09 at 9 09 07 AM](https://user-images.githubusercontent.com/26442605/224102962-d0222578-3f10-4566-856d-8d59f28fcf2e.png)
10. `copilot` uzantısı, VS Code uzantıları listesinde görünmelidir. Uzantılar yan menüsüne tıklayın. Aşağıdakileri görmelisiniz:  
   ![Screen Shot 2023-03-09 at 9 04 13 AM](https://user-images.githubusercontent.com/26442605/224102514-7d6d2f51-f435-401d-a529-7bae3ae3e511.png)

**Yaklaşık 60 saniye bekleyin, ardından bir sonraki adım için repository ana sayfanızı yenileyin.**

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
