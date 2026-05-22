<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tea Time History - Historical Gossip & Tea</title>
    <!-- Tailwind CSS for sleek pastel layouts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        pastelPink: '#FFDEE9',
                        pastelBlue: '#B5FFFC',
                        pastelPurple: '#E2D9F3',
                        pastelPeach: '#FFECD2',
                        pastelMint: '#E8F5E9',
                        textDark: '#4A4E69'
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts for retro/playful elegant look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@300..700&family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <style>
        body {
            font-family: 'Quicksand', sans-serif;
            background: linear-gradient(135deg, #FFDEE9 0%, #B5FFFC 100%);
            min-height: 100vh;
            color: #4A4E69;
        }
        h1, h2, h3, .font-title {
            font-family: 'Fredoka', sans-serif;
        }
        /* Custom scrollbar for an aesthetic feel */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #FFDEE9;
        }
        ::-webkit-scrollbar-thumb {
            background: #B5FFFC;
            border-radius: 10px;
        }
        .gossip-card {
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .gossip-card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="py-8 px-4 flex flex-col items-center">

    <!-- Notification Toast -->
    <div id="toast" class="fixed top-5 right-5 z-50 bg-white text-textDark px-6 py-3 rounded-full shadow-lg border border-pastelPurple hidden flex items-center gap-2 transform translate-y-[-20px] transition-all duration-300">
        <span id="toast-icon">✨</span> <span id="toast-message" class="font-medium"></span>
    </div>

    <!-- Header / Banner -->
    <header class="text-center max-w-xl mb-8">
        <div class="inline-block bg-white/70 backdrop-blur-md px-6 py-2 rounded-full text-sm font-semibold tracking-wider text-[#9C8EB9] mb-3 border border-white/50 shadow-sm">
            👑 THE ULTIMATE HISTORICAL TEA
        </div>
        <h1 class="text-4xl md:text-5xl font-bold text-[#6D597A] tracking-tight leading-tight">
            Spilling Historical Tea ☕
        </h1>
        <p class="text-lg text-[#8E7C93] mt-2 font-medium">
            Wild, funny, and absolutely scandalous gossip from the elite of the past.
        </p>
    </header>

    <main class="w-full max-w-2xl">
        <!-- Interactive search/filter -->
        <div class="mb-6 flex flex-wrap gap-2 justify-center">
            <button onclick="filterEra('all')" class="px-4 py-2 rounded-full bg-white text-textDark font-semibold text-sm border-2 border-white hover:border-pastelPurple transition shadow-sm active-filter">All Tea 🫖</button>
            <button onclick="filterEra('Ancient')" class="px-4 py-2 rounded-full bg-white/60 text-[#6D597A] font-semibold text-sm border border-white/50 hover:bg-white transition shadow-sm">Ancient Rome/Egypt 🏛️</button>
            <button onclick="filterEra('French')" class="px-4 py-2 rounded-full bg-white/60 text-[#6D597A] font-semibold text-sm border border-white/50 hover:bg-white transition shadow-sm">Royal France 👑</button>
            <button onclick="filterEra('Victorian')" class="px-4 py-2 rounded-full bg-white/60 text-[#6D597A] font-semibold text-sm border border-white/50 hover:bg-white transition shadow-sm">Victorian Drama 🐻</button>
        </div>

        <!-- Section to Add New Gossip -->
        <section class="bg-white/85 backdrop-blur-md p-6 rounded-[2rem] shadow-xl border border-white/80 mb-8">
            <h2 class="text-2xl font-bold text-[#6D597A] mb-2 flex items-center gap-2">
                <i class="fa-solid fa-bullhorn text-[#E89EBE]"></i> Spill Your Own Tea!
            </h2>
            <p class="text-sm text-[#8E7C93] mb-4">Did you discover an outrageous fact? Type it below to post it instantly in this session.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-3 mb-3">
                <div>
                    <label class="block text-xs font-bold text-[#8E7C93] mb-1 uppercase tracking-wider">Historical Era</label>
                    <input type="text" id="form-era" placeholder="e.g., French Royalty, Ancient Greece" class="w-full px-4 py-2.5 rounded-2xl border-2 border-dashed border-[#E2D9F3] bg-white/50 focus:outline-none focus:border-[#C7B8E3] focus:bg-white text-sm transition">
                </div>
                <div>
                    <label class="block text-xs font-bold text-[#8E7C93] mb-1 uppercase tracking-wider">Your Pen Name</label>
                    <input type="text" id="form-author" placeholder="e.g., Gossip Girl 1789, Anonymous Noble" class="w-full px-4 py-2.5 rounded-2xl border-2 border-dashed border-[#E2D9F3] bg-white/50 focus:outline-none focus:border-[#C7B8E3] focus:bg-white text-sm transition">
                </div>
            </div>
            
            <div class="mb-4">
                <label class="block text-xs font-bold text-[#8E7C93] mb-1 uppercase tracking-wider">The Spicy Details</label>
                <textarea id="form-content" rows="3" placeholder="Tell us the scandal! (Keep it fun, English only)..." class="w-full px-4 py-3 rounded-2xl border-2 border-dashed border-[#E2D9F3] bg-white/50 focus:outline-none focus:border-[#C7B8E3] focus:bg-white text-sm transition resize-none"></textarea>
            </div>

            <button onclick="addGossip()" class="w-full py-3 bg-[#E89EBE] hover:bg-[#D987AA] text-white font-bold rounded-2xl shadow-md transition-all flex items-center justify-center gap-2">
                <i class="fa-solid fa-paper-plane"></i> Publish to Feed
            </button>
        </section>

        <!-- Gossip Feed Container -->
        <div id="feed" class="space-y-6">
            <!-- Feed will be injected dynamically here -->
        </div>
    </main>

    <footer class="mt-12 text-center text-sm text-[#8E7C93] font-medium">
        <p>Made with 💖 for history lovers | Interactivity simulation active</p>
    </footer>

    <script>
        // Initial "Gossip" Data with beautiful retrieved pastel history portrait images
        const initialGossip = [
            {
                id: 1,
                era: "Ancient Rome",
                category: "Ancient",
                author: "NobleInsider_44",
                image: "http://googleusercontent.com/image_collection/image_retrieval/10993079694724017253_0",
                content: "Did you know Roman Emperor Caligula loved his horse, Incitatus, so much that he gave him a marble stable, a golden collar, and literally planned to make him a senator? Talk about elite pet privilege. 🐴✨",
                likes: 128,
                comments: ["Are we sure the horse wasn't just a great politician?", "Honestly, I trust the horse over most rulers."]
            },
            {
                id: 2,
                era: "French Royalty",
                category: "French",
                author: "Versailles_Tease",
                image: "http://googleusercontent.com/image_collection/image_retrieval/10993079694724017253_1",
                content: "King Louis XIV (The Sun King) basically made everyone watch him wake up, eat, and even use the toilet as a massive power move. If you weren't invited to watch him put on his royal pants, you were a nobody in Versailles. 👑💀",
                likes: 245,
                comments: ["Imagine having an audience while trying to find a matching sock.", "The absolute original reality TV star."]
            },
            {
                id: 3,
                era: "Victorian Era",
                category: "Victorian",
                author: "Byron_Bear_Club",
                image: "http://googleusercontent.com/image_collection/image_retrieval/10993079694724017253_2",
                content: "Lord Byron was banned from keeping a pet dog at his Cambridge college room, so he found a loophole: he brought a tame BEAR instead! The regulations didn't mention bears, so they couldn't stop him. Absolute genius. bear",
                likes: 312,
                comments: ["Malicious compliance at its finest!", "Byron was the drama king of the century."]
            },
            {
                id: 4,
                era: "Ancient Egypt",
                category: "Ancient",
                author: "Nile_Queen_Secret",
                image: "http://googleusercontent.com/image_collection/image_retrieval/10993079694724017253_3",
                content: "Cleopatra once won a bet against Mark Antony that she could consume an entire multi-million sesterce feast in a single meal. She simply dissolved a massive priceless pearl from her earring in a glass of sour vinegar and drank it! 💎🍷",
                likes: 189,
                comments: ["Rich people problems, historical edition.", "An iconic power move!"]
            }
        ];

        let currentFilter = 'all';

        // Show elegant custom toast notification
        function showToast(message, icon = '✨') {
            const toast = document.getElementById('toast');
            const toastMessage = document.getElementById('toast-message');
            const toastIcon = document.getElementById('toast-icon');
            
            toastIcon.innerText = icon;
            toastMessage.innerText = message;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.remove('translate-y-[-20px]');
                toast.classList.add('translate-y-0');
            }, 50);

            setTimeout(() => {
                toast.classList.add('translate-y-[-20px]');
                setTimeout(() => {
                    toast.classList.add('hidden');
                }, 300);
            }, 3000);
        }

        // Render Feed dynamically with beautiful pastel card styles and interactive actions
        function renderFeed() {
            const feed = document.getElementById('feed');
            feed.innerHTML = '';

            const filteredList = currentFilter === 'all' 
                ? initialGossip 
                : initialGossip.filter(post => post.category === currentFilter);

            if (filteredList.length === 0) {
                feed.innerHTML = `
                    <div class="text-center p-8 bg-white/50 rounded-2xl border border-white">
                        <p class="font-semibold text-[#8E7C93]">No tea has been spilled in this category yet. Be the first!</p>
                    </div>
                `;
                return;
            }

            // Beautiful soft colors rotated for cards
            const colors = [
                { bg: 'bg-white', border: 'border-pastelPink/50', accent: '#E89EBE', text: 'text-[#E89EBE]' },
                { bg: 'bg-white', border: 'border-pastelBlue/50', accent: '#70D6FF', text: 'text-[#56C3EE]' },
                { bg: 'bg-white', border: 'border-pastelPurple/50', accent: '#BE95C4', text: 'text-[#BE95C4]' },
                { bg: 'bg-white', border: 'border-pastelPeach/50', accent: '#FFD166', text: 'text-[#E0A926]' }
            ];

            filteredList.forEach((post, index) => {
                const colorStyle = colors[index % colors.length];
                const card = document.createElement('article');
                card.className = `gossip-card ${colorStyle.bg} border-2 ${colorStyle.border} p-5 rounded-[2.5rem] shadow-md flex flex-col gap-4 overflow-hidden`;
                
                // Build list of comments dynamically
                const commentsHTML = post.comments.map(c => `
                    <li class="bg-gray-50/70 p-3 rounded-2xl text-xs md:text-sm font-medium text-textDark/90 shadow-sm border border-white/50">
                        💬 ${c}
                    </li>
                `).join('');

                card.innerHTML = `
                    <!-- Top Info Header -->
                    <div class="flex justify-between items-center text-xs">
                        <span class="bg-pastelPurple/60 text-[#6D597A] px-3.5 py-1.5 rounded-full font-bold tracking-wide">
                            📍 ${post.era}
                        </span>
                        <span class="text-gray-400 font-semibold flex items-center gap-1">
                            <i class="fa-solid fa-user-ninja"></i> by @${post.author}
                        </span>
                    </div>

                    <!-- Layout: Image and Text Side-by-Side (or stacked on mobile) -->
                    <div class="flex flex-col md:flex-row gap-4 items-start">
                        ${post.image ? `
                        <div class="w-full md:w-44 h-44 rounded-3xl overflow-hidden shadow-sm flex-shrink-0 border-2 border-white">
                            <img src="${post.image}" alt="Historical representation" class="w-full h-full object-cover">
                        </div>
                        ` : ''}
                        <div class="flex-grow">
                            <p class="text-base font-semibold leading-relaxed text-textDark/90">
                                "${post.content}"
                            </p>
                        </div>
                    </div>

                    <!-- Interactions Bar -->
                    <div class="flex items-center gap-2 pt-2 border-t border-gray-100">
                        <button onclick="likePost(${post.id})" class="flex items-center gap-2 bg-[#FFF0F5] hover:bg-[#FFE0EB] text-[#E89EBE] px-4 py-2 rounded-full text-sm font-bold transition shadow-sm">
                            <i class="fa-solid fa-heart animate-pulse"></i> 
                            <span id="like-count-${post.id}">${post.likes}</span> Likes
                        </button>
                        
                        <button onclick="sharePost(${post.id}, '${post.era}')" class="flex items-center gap-2 bg-pastelBlue/50 hover:bg-pastelBlue text-[#4FA3A5] px-4 py-2 rounded-full text-sm font-bold transition shadow-sm ml-auto">
                            <i class="fa-solid fa-share-nodes"></i> Share
                        </button>
                    </div>

                    <!-- Comments Section -->
                    <div class="mt-2 bg-[#FAF9FF] p-4 rounded-3xl border border-pastelPurple/20">
                        <h4 class="text-xs font-bold text-[#8E7C93] uppercase tracking-wider mb-2 flex items-center gap-1">
                            <i class="fa-regular fa-comments text-pastelPurple"></i> Replies (${post.comments.length})
                        </h4>
                        
                        <ul class="space-y-2 mb-3 max-h-48 overflow-y-auto pr-1" id="comments-${post.id}">
                            ${commentsHTML}
                        </ul>

                        <!-- Reply Input Form -->
                        <div class="flex gap-2">
                            <input type="text" id="input-${post.id}" placeholder="Drop your reply..." class="flex-1 px-4 py-2 text-xs md:text-sm rounded-full border-2 border-white/60 focus:outline-none focus:border-pastelPurple/80 bg-white/50 text-textDark shadow-sm">
                            <button onclick="addComment(${post.id})" class="bg-[#E2D9F3] hover:bg-[#D3C4EA] text-[#6D597A] font-bold px-4 rounded-full text-xs md:text-sm transition shadow-sm">
                                Reply
                            </button>
                        </div>
                    </div>
                `;
                feed.appendChild(card);
            });
        }

        // Like Counter handler
        function likePost(id) {
            const post = initialGossip.find(p => p.id === id);
            if (post) {
                post.likes++;
                document.getElementById(`like-count-${id}`).innerText = post.likes;
                showToast("Liked this juicy gossip! ❤️", "🥰");
            }
        }

        // Custom Share trigger
        function sharePost(id, era) {
            const tempUrl = window.location.href;
            navigator.clipboard.writeText(tempUrl);
            showToast(`Scandal link about ${era} copied! Share it! ☕`, "🔗");
        }

        // Comment reply addition
        function addComment(id) {
            const input = document.getElementById(`input-${id}`);
            const commentText = input.value.trim();
            
            if (commentText === '') {
                showToast("Write a reply first!", "❌");
                return;
            }

            const post = initialGossip.find(p => p.id === id);
            if (post) {
                post.comments.push(commentText);
                
                // Refresh list directly for smooth experience
                const commentList = document.getElementById(`comments-${id}`);
                const newComment = document.createElement('li');
                newComment.className = "bg-gray-50/70 p-3 rounded-2xl text-xs md:text-sm font-medium text-textDark/90 shadow-sm border border-white/50";
                newComment.innerHTML = `💬 ${commentText}`;
                commentList.appendChild(newComment);
                
                // Clear input
                input.value = '';
                showToast("Reply posted successfully! ✨", "💬");
                
                // Refresh full render to sync count badge
                setTimeout(() => renderFeed(), 1000);
            }
        }

        // Filter events by Era Group
        function filterEra(era) {
            currentFilter = era;
            
            // Adjust active CSS states dynamically
            const buttons = document.querySelectorAll('main div button');
            buttons.forEach(btn => {
                if (btn.innerText.toLowerCase().includes(era.toLowerCase()) || (era === 'all' && btn.innerText.includes('All'))) {
                    btn.className = "px-4 py-2 rounded-full bg-white text-[#6D597A] font-bold text-sm border-2 border-pastelPurple shadow-sm transition";
                } else {
                    btn.className = "px-4 py-2 rounded-full bg-white/60 text-[#8E7C93] font-semibold text-sm border border-white/50 hover:bg-white transition shadow-sm";
                }
            });

            renderFeed();
        }

        // Create and prepend custom User Gossip
        function addGossip() {
            const eraInput = document.getElementById('form-era');
            const authorInput = document.getElementById('form-author');
            const contentInput = document.getElementById('form-content');

            const era = eraInput.value.trim() || "Mysterious Era";
            const author = authorInput.value.trim() || "AnonymousTea";
            const content = contentInput.value.trim();

            if (content === '') {
                showToast("You need to spill some actual tea to post! ☕", "⚠️");
                return;
            }

            const newPost = {
                id: Date.now(),
                era: era,
                category: "Custom",
                author: author,
                // Optional random vintage portrait as placeholder for custom user posts
                image: "http://googleusercontent.com/image_collection/image_retrieval/10993079694724017253_" + Math.floor(Math.random() * 4),
                content: content,
                likes: 0,
                comments: []
            };

            // Unshift places the newly posted gossip right at the top
            initialGossip.unshift(newPost);
            
            // Reset active filter to show the new post instantly
            currentFilter = 'all';
            
            // Reset fields
            eraInput.value = '';
            authorInput.value = '';
            contentInput.value = '';

            renderFeed();
            showToast("Tea spilled! Your post is live on the feed below. 📣", "🥳");
        }

        // Initial setup execution
        renderFeed();
    </script>
</body>
