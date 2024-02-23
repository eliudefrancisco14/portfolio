<template>
    <div>
        <header>
            <nav>
                <NuxLink to="/">Home</NuxLink>
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

