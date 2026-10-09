// 禁用右键菜单
document.addEventListener('contextmenu', e => e.preventDefault());

// 禁用 F12 和常见开发者工具快捷键
document.addEventListener('keydown', e => {
    if (e.key === 'F12' || (e.ctrlKey && e.shiftKey && (e.key === 'I' || e.key === 'J' || e.key === 'C')) || (e.ctrlKey && e.key === 'U')) {
        e.preventDefault();
    }
});