<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <Nux-link to="/">Home</Nux-link>
                <ul>
                    <li><NuxLink to="/project">Projectos</NuxLink></li>
                    <li><NuxLink to="/blog">Blog</NuxLink></li>
                    <li><NuxLink to="/speak">Speak</NuxLink></li>
                </ul>
            </nav>
        </header>

        <div>
            <slot />
        </div>

    </div>
</template>

